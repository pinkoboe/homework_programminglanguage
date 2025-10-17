# homework_programminglanguage
# 파일을 불러옵니다.
with open('yesterday.txt', 'r') as f:
    yesterday_lyric = f.read()

yesterday_lyric
# TODO: Your code here
yesterday_lyric=yesterday_lyric.lower()
print(f"Yesterday 개수: {yesterday_lyric.count('yesterday')}")


# TODO: Your code here
with open('yesterday.txt', 'r') as f:
    yesterday_lyric = f.read()

yesterday_lyric
print(f"Yesterday 개수: {yesterday_lyric.count('Yesterday')}")
print(f"yesterday 개수: {yesterday_lyric.count('yesterday')}")
