[Upload<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>나만의 중고마켓</title>
    <link rel="stylesheet"
        href="https://s3.ap-northeast-2.amazonaws.com/materials.spartacodingclub.kr/easygpt/default.css" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous" />
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4"
        crossorigin="anonymous"></script>
    <style>
        /* Hero 스타일 */
        .hero-section {
            background-color: #343a40;
            color: white;
            padding: 80px 0;
            /* 위아래 여백 조정 */
            text-align: center;
            margin-bottom: 20px;
            /* 아래쪽 여백 추가 */
        }

        .hero-section h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
            /* 아래쪽 여백 추가 */
        }

        .hero-section p {
            font-size: 1.5em;
        }


        /* 카드 스타일 */
        .card {
            transition: transform 0.3s ease-in-out;
            /* 변화에 대한 부드러운 애니메이션 속성 추가 */
        }

        /* 마우스를 올렸을 때의 스타일 */
        .card:hover {
            transform: scale(1.05);
            /* 5% 증가하는 크기 변환 */
        }
    </style>

</head>

<body>
    <div class="hero bg-dark text-center py-5">
        <h1 class="text-white">나만의 르탄마켓</h1>
        <h2 class="text-white">집에 있는 물건을 팝니다!</h2>
    </div>
    <div class="container mt-5">
        <div class="row">
            <!-- 냄비 카드 -->
            <div class="col-md-4">
                <div class="card" style="width: 18rem">
                    <img src="https://images.unsplash.com/photo-1590794056226-79ef3a8147e1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8cG90fGVufDB8fDB8fHww&auto=format&fit=crop&w=500&q=60"
                        class="card-img-top" alt="냄비 이미지" />
                    <div class="card-body">
                        <h5 class="card-title">냄비</h5>
                        <h6 class="card-subtitle mb-2 text-muted">5만원</h6>
                        <p class="card-text">
                            한 번 밖에 안 쓴 냄비 팝니다. 부모님이 독립할 때 주신 거에요!
                        </p>
                        <a href="https://spartacodingclub.kr/" class="btn btn-primary" target="_blank"
                            rel="noopener noreferrer">
                            상세 정보 보기
                        </a>
                    </div>
                </div>
            </div>
            <!-- 전기밥솥 카드 -->
            <div class="col-md-4">
                <div class="card" style="width: 18rem">
                    <img src="https://images.unsplash.com/photo-1544233726-9f1d2b27be8b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8JUVCJUIwJUE1JUVDJTg2JUE1fGVufDB8fDB8fHww&auto=format&fit=crop&w=500&q=60"
                        class="card-img-top" alt="전기밥솥 이미지" />
                    <div class="card-body">
                        <h5 class="card-title">전기밥솥</h5>
                        <h6 class="card-subtitle mb-2 text-muted">8만원</h6>
                        <p class="card-text">
                            거의 사용하지 않은 전기밥솥 팝니다. 상태 양호합니다.
                        </p>
                        <a href="https://spartacodingclub.kr/" class="btn btn-primary" target="_blank"
                            rel="noopener noreferrer">
                            상세 정보 보기
                        </a>
                    </div>
                </div>
            </div>
            <!-- 주전자 카드 -->
            <div class="col-md-4">
                <div class="card" style="width: 18rem">
                    <img src="https://images.unsplash.com/photo-1622088934558-b729cf3c8cf8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8JUVCJUFDJUJDJTIwJUVDJUEzJUJDJUVDJUEwJTg0JUVDJTlFJTkwfGVufDB8fDB8fHww&auto=format&fit=crop&w=500&q=60"
                        class="card-img-top" alt="주전자 이미지" />
                    <div class="card-body">
                        <h5 class="card-title">주전자</h5>
                        <h6 class="card-subtitle mb-2 text-muted">3만원</h6>
                        <p class="card-text">
                            사용감이 있지만 기능에는 문제 없는 주전자 팝니다.
                        </p>
                        <a href="https://spartacodingclub.kr/" class="btn btn-primary" target="_blank"
                            rel="noopener noreferrer">
                            상세 정보 보기
                        </a>
                    </div>
                </div>
            </div>
            <div class="col-md-4">
                <div class="card" style="width: 18rem">
                    <img src="https://images.unsplash.com/photo-1590794056226-79ef3a8147e1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8cG90fGVufDB8fDB8fHww&auto=format&fit=crop&w=500&q=60"
                        class="card-img-top" alt="냄비 이미지" />
                    <div class="card-body">
                        <h5 class="card-title">냄비</h5>
                        <h6 class="card-subtitle mb-2 text-muted">5만원</h6>
                        <p class="card-text">
                            한 번 밖에 안 쓴 냄비 팝니다. 부모님이 독립할 때 주신 거에요!
                        </p>
                        <a href="https://spartacodingclub.kr/" class="btn btn-primary" target="_blank"
                            rel="noopener noreferrer">
                            상세 정보 보기
                        </a>
                    </div>
                </div>
            </div>
            <!-- 전기밥솥 카드 -->
            <div class="col-md-4">
                <div class="card" style="width: 18rem">
                    <img src="https://images.unsplash.com/photo-1544233726-9f1d2b27be8b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8JUVCJUIwJUE1JUVDJTg2JUE1fGVufDB8fDB8fHww&auto=format&fit=crop&w=500&q=60"
                        class="card-img-top" alt="전기밥솥 이미지" />
                    <div class="card-body">
                        <h5 class="card-title">전기밥솥</h5>
                        <h6 class="card-subtitle mb-2 text-muted">8만원</h6>
                        <p class="card-text">
                            거의 사용하지 않은 전기밥솥 팝니다. 상태 양호합니다.
                        </p>
                        <a href="https://spartacodingclub.kr/" class="btn btn-primary" target="_blank"
                            rel="noopener noreferrer">
                            상세 정보 보기
                        </a>
                    </div>
                </div>
            </div>
            <!-- 주전자 카드 -->
            <div class="col-md-4">
                <div class="card" style="width: 18rem">
                    <img src="https://images.unsplash.com/photo-1622088934558-b729cf3c8cf8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8JUVCJUFDJUJDJTIwJUVDJUEzJUJDJUVDJUEwJTg0JUVDJTlFJTkwfGVufDB8fDB8fHww&auto=format&fit=crop&w=500&q=60"
                        class="card-img-top" alt="주전자 이미지" />
                    <div class="card-body">
                        <h5 class="card-title">주전자</h5>
                        <h6 class="card-subtitle mb-2 text-muted">3만원</h6>
                        <p class="card-text">
                            사용감이 있지만 기능에는 문제 없는 주전자 팝니다.
                        </p>
                        <a href="https://spartacodingclub.kr/" class="btn btn-primary" target="_blank"
                            rel="noopener noreferrer">
                            상세 정보 보기
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>

</html>ing index.html…]()
