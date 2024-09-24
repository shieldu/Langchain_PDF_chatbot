# Langchain_PDF_ChatBot 📄🤖

## Description
OpenAI API와 Langchain 라이브러리를 활용하여 첨부한 PDF 파일을 바탕으로 대화를 할 수 있는 챗봇입니다. 사용자가 업로드한 PDF 파일의 내용을 처리하고, 그 내용을 바탕으로 질문에 답변하는 챗봇입니다.

## Installation and Execution

### Requirements
프로그램을 실행하기 위해 필요한 라이브러리들이 `requirements.txt` 파일에 명시되어 있습니다. 다음 명령어로 필요한 라이브러리들을 설치하세요:

```bash
pip install -r requirements.txt
```

`requirements.txt` 파일에는 다음 라이브러리들이 포함되어 있습니다:
- flask
- langchain
- chromadb
- sentence-transformers
- openai
- pypdf
- langchain-community
- python-dotenv

### 만약 requirements.txt가 안된다면
다음은 마크다운 형식으로 각 라이브러리 설치 명령어를 분리한 내용입니다:

```bash
pip install flask
```

```bash
pip install langchain
```

```bash
pip install chromadb
```

```bash
pip install sentence-transformers
```

```bash
pip install openai
```

```bash
pip install pypdf
```

```bash
pip install langchain-community
```

```bash
pip install python-dotenv
```


### 실행 방법
1. OpenAI API 키를 `.env` 파일에 저장하세요:
```
OPENAI_API_KEY=your_openai_api_key
```

2. `app.py` 파일을 실행하여 웹 애플리케이션을 시작하세요:
```bash
python app.py
```

3. 웹 브라우저에서 `http://localhost:5000`으로 이동하여 PDF 파일을 업로드하고 질문을 입력하세요.

