<br />
<br />

<!-- Header -->

<div align="middle" >
  <img width="120px;" src="https://emojipedia-us.s3.dualstack.us-west-1.amazonaws.com/thumbs/320/apple/285/couch-and-lamp_1f6cb-fe0f.png"/>
</div>

<h1 align="middle">The House of Tomorrow</h2>
<p align="middle">Online lifestyle shop made with SASS</p>

<p align="middle">
  <img src="https://img.shields.io/badge/version-1.0.0-F1F0E7?style=flat-square" alt="template version"/>
  <img src="https://img.shields.io/badge/language-HTML-F1652A.svg?style=flat-square"/>
  <img src="https://img.shields.io/badge/language-SASS-BF4080"/>
  <img src="https://img.shields.io/badge/license-MIT-8B8C8D.svg?style=flat-square"/>
</p>

<!-- <p align="middle"><a href="#">π Project link</a></p> -->

<br />
<br />

<!-- Content -->

## πΈ screenshots

<img src="https://user-images.githubusercontent.com/46529118/141482440-2b816eee-9778-4913-a2a7-d82260703283.png" />

<br />
<br />

<h2>β Status</h2>

<br />

### 1. Login & Logout Status: λ‘κ·ΈμΈ νμ λ & λ‘κ·ΈμΈ μ νμ λ

<br />

### 1-1. GNB

- λ‘κ·ΈμΈ μ νμ λ

```html
<div class="button-group">
  <button
    class="gnb-icon-button is-search lg-hidden"
    type="button"
    aria-label="κ²μ μ΄κΈ° λ²νΌ"
  >
    <i class="ic-search"></i>
  </button>
  <a
    class="gnb-icon-button is-cart"
    href="/"
    aria-label="μ₯λ°κ΅¬λλ‘ νμ΄μ§λ‘ μ΄λ"
  >
    <i class="ic-cart"></i>
  </a>
  <div class="gnb-auth sm-hidden">
    <a href="/">λ‘κ·ΈμΈ</a>
    <a href="/">νμκ°μ</a>
  </div>
</div>
```

<br />

- λ‘κ·ΈμΈ νμ λ

```html
<div class="button-group">
  <button
    class="gnb-icon-button is-search lg-hidden"
    type="button"
    aria-label="κ²μ μ΄κΈ° λ²νΌ"
  >
    <i class="ic-search"></i>
  </button>

  <a
    class="gnb-icon-button sm-hidden"
    href="/"
    aria-label="μ€ν¬λ©λΆ νμ΄μ§λ‘ μ΄λ"
  >
    <i class="ic-bookmark"></i>
  </a>

  <a
    class="gnb-icon-button sm-hidden"
    href="/"
    aria-label="λ΄ μμ νμ΄μ§λ‘ μ΄λ"
  >
    <i class="ic-bell"></i>
  </a>

  <a
    class="gnb-icon-button is-cart"
    href="/"
    aria-label="μ₯λ°κ΅¬λλ‘ νμ΄μ§λ‘ μ΄λ"
  >
    <i class="ic-cart"></i>
    <strong class="badge" aria-label="μ₯λ°κ΅¬λμ μνμ΄ 5κ° λ΄κ²¨ μμ΅λλ€"
      >5</strong
    >
  </a>

  <button
    class="gnb-avatar-button sm-hidden"
    type="button"
    aria-label="λ§μ΄ λ©λ΄ μ΄κΈ° λ²νΌ"
  >
    <div class="avatar-32">
      <img
        src="https://static.wikia.nocookie.net/characters/images/1/19/Sally_Fantasia.jpg"
        alt="User image"
      />
    </div>
  </button>
</div>
```

<br />
<br />

### 1-2. Sidebar

#### 1-2-1. User avatar & user name

- λ‘κ·ΈμΈ νμ λ

```html
<div class="sidebar-user">
  <a href="/">
    <div class="avatar-24">
      <img src="./assets/images/img-user-01.jpg" alt="User image" />
    </div>
    <strong class="user-name">
      μ‘°μ§ κ±°μμ μ‘°μ§ κ±°μμ μ‘°μ§ κ±°μμ μ‘°μ§ κ±°μμ μ‘°μ§ κ±°μμ μ‘°μ§ κ±°μμ
    </strong></a
  >
</div>
```

- λ‘κ·ΈμΈ μ νμ λ

```html
<div class="sidebar-auth">
  <a href="/" class="btn-outlined btn-40">λ‘κ·ΈμΈ</a>
  <a href="/" class="btn-fill-primary btn-40">νμκ°μ</a>
</div>
```

#### 1-2-2. My menu

- λ‘κ·ΈμΈ νμ λ

```html
<div class="sidebar-menu-my">
  <ul class="sidebar-menu-my-list">
    <li class="sidebar-menu-my-list-item">
      <a href="/">λ§μ΄νμ΄μ§</a>
    </li>
    <li class="sidebar-menu-my-list-item">
      <a href="/">λμ μΌν</a>
    </li>
    <li class="sidebar-menu-my-list-item">
      <a href="/">μ€ν¬λ©λΆ</a>
    </li>
    <li class="sidebar-menu-my-list-item">
      <a href="/">μλ¦Ό</a>
    </li>
    <li class="sidebar-menu-my-list-item">
      <a href="/">μ΄λ²€νΈ </a>
    </li>
  </ul>
</div>
```

- λ‘κ·ΈμΈ μ νμ λ: none

  <br />
  <br />

### 2. Review

- Review μμ λ

```html
<section
  class="product-section product-review"
  id="product-review"
  role="tabpanel"
>
  <header class="product-section-header">
    <h1 class="title">λ¦¬λ·°</h1>
    <strong class="badge" aria-label="0κ°">0</strong>
    <a class="text-button" href="/">λ¦¬λ·°μ°κΈ°</a>
  </header>

  <div class="product-section-content">
    <p class="review-empty">
      μ²« λ¦¬λ·°λ₯Ό λ¨κ²¨μ£ΌμΈμ! <br />
      μ΅λ <strong>500P</strong>λ₯Ό λλ¦½λλ€.
    </p>
  </div>
</section>
```

- Review μμ λ

```html
<section
  class="product-section product-review"
  id="product-review"
  role="tabpanel"
>
  <header class="product-section-header">
    <h1 class="title">λ¦¬λ·°</h1>
    <strong class="badge" aria-label="566κ°">566</strong>
    <a class="text-button" href="/">λ¦¬λ·°μ°κΈ°</a>
  </header>

  <div class="product-section-content">
    <div class="review-scoreboard">
      <div class="score-summary">
        <strong class="average-score" aria-label="νμ  4.8">4.8</strong>
        <div class="star-rating">
          <i class="ic-star is-active"></i>
          <i class="ic-star is-active"></i>
          <i class="ic-star is-active"></i>
          <i class="ic-star is-active"></i>
          <i class="ic-star is-active"></i>
        </div>
      </div>

      <div class="score-detail">
        <dl class="score-stats-list">
          <div class="score-stats-item is-active">
            <dt>5μ </dt>

            <dd>
              <div class="bar-graph" aria-hidden="true">
                <div class="active-bar"></div>
              </div>
              <strong class="count" aria-label="467λͺ">467</strong>
            </dd>
          </div>

          <div class="score-stats-item">
            <dt>4μ </dt>

            <dd>
              <div class="bar-graph" aria-hidden="true">
                <div class="active-bar"></div>
              </div>
              <strong class="count" aria-label="87λͺ">87</strong>
            </dd>
          </div>

          <div class="score-stats-item">
            <dt>3μ </dt>

            <dd>
              <div class="bar-graph" aria-hidden="true">
                <div class="active-bar"></div>
              </div>
              <strong class="count" aria-label="13λͺ">13</strong>
            </dd>
          </div>

          <div class="score-stats-item">
            <dt>2μ </dt>
            <dd>
              <div class="bar-graph" aria-hidden="true">
                <div class="active-bar"></div>
              </div>
              <strong class="count" aria-label="0λͺ">0</strong>
            </dd>
          </div>

          <div class="score-stats-item">
            <dt>1μ </dt>

            <dd>
              <div class="bar-graph" aria-hidden="true">
                <div class="active-bar"></div>
              </div>
              <strong class="count" aria-label="0λͺ">0</strong>
            </dd>
          </div>
        </dl>
      </div>
    </div>

    <ol class="review-list">
      <li class="review-item">
        <article class="review-card">
          <header class="review-card-header">
            <h3 class="visually-hidden">λ§₯λͺ¨λλΆμ¬μΌκ²¬ λμ΄ μμ±ν λ¦¬λ·°</h3>

            <a class="avatar-24" href="/">
              <img
                src="./assets/images/img-user-04.jpeg"
                alt="λ§₯λͺ¨λλΆμ¬μΌκ²¬ λμ νλ‘ν μ΄λ―Έμ§"
              />
            </a>

            <div class="info">
              <a class="username" href="/"><strong>λ§₯λͺ¨λλΆμ¬μΌκ²¬</strong></a>

              <div class="detail">
                <div class="star-rating-13" aria-label="5.0μ  μ€μ 5.0μ ">
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                </div>

                <div class="misc">
                  <time>2021.01.01</time>
                  <span>μ€λμμ§ κ΅¬λ§€</span>
                </div>
              </div>
            </div>
          </header>

          <div class="review-card-body">
            <p>
              μ§ μ μ²΄λ₯Ό λ°μ΄λ€κΈ°λ³΄λ€λ νμ΄λκ³  μμ μμμμΌλ©΄ λ°λν΄μ§λ
              μ λμμ. λΆ κΊΌλκ³  λλ‘ μΌκ³  λ΄μ λ?μ μ±λ‘ μ»€νΌ λ§μλ©΄ μμ£Ό
              μ’μμ. κ³ μμ΄λ μ’μν΄μ
            </p>
          </div>

          <footer class="review-card-footer">
            <button class="btn-outlined btn-32" type="button">
              λμμ΄ λΌμ
            </button>

            <p>
              <strong><span>7</span>λͺ</strong>μκ² λμμ΄ λμμ΅λλ€.
            </p>
          </footer>
        </article>
      </li>

      <!-- NOTE: Review Image β -->
      <li class="review-item">
        <article class="review-card">
          <header class="review-card-header">
            <h3 class="visually-hidden">
              μν¬λ¦Ό λμ΄κ° μ΄λ¦½λλ€ λμ΄ μμ±ν λ¦¬λ·°
            </h3>

            <a
              class="avatar-24"
              href="/"
              aria-label="μν¬λ¦Ό λμ΄κ° μ΄λ¦½λλ€ λμ νλ‘νλ‘ μ΄λ"
            >
            </a>

            <div class="info">
              <a class="username" href="/"
                ><strong>μν¬λ¦Ό λμ΄κ° μ΄λ¦½λλ€</strong></a
              >

              <div class="detail">
                <div class="star-rating-13" aria-label="5.0μ  μ€μ 5.0μ ">
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star"></i>
                </div>

                <div class="misc">
                  <time>2021.01.01</time>
                  <span>μ€λμμ§ κ΅¬λ§€</span>
                </div>
              </div>
            </div>
          </header>

          <div class="review-card-body">
            <p>
              μ¨λ μ‘°μ κ³Ό νμ΄λ¨Έκ° μ λλ€λ κ±Έ λ€λ¦κ² μμμ§λ§ μ΄μλκΉ λλ§μ‘±!
              κ°κ²©λ λλ§μ‘±!
            </p>
          </div>

          <footer class="review-card-footer">
            <button class="btn-outlined btn-32" type="button">
              λμμ΄ λΌμ
            </button>

            <p>
              <strong><span>7</span>λͺ</strong>μκ² λμμ΄ λμμ΅λλ€.
            </p>
          </footer>
        </article>
      </li>

      <!-- NOTE: Review Image β­οΈ -->
      <li class="review-item">
        <article class="review-card">
          <header class="review-card-header">
            <h3 class="visually-hidden">ν λΆλ‘ μ ννκ² λμ΄ μμ±ν λ¦¬λ·°</h3>

            <a class="avatar-24" href="/">
              <img
                src="./assets/images/img-user-02.jpeg"
                alt="ν λΆλ‘ μ ννκ² λμ νλ‘ν μ΄λ―Έμ§"
              />
            </a>

            <div class="info">
              <a class="username" href="/"><strong>ν λΆλ‘ μ ννκ²</strong></a>

              <div class="detail">
                <div class="star-rating-13" aria-label="5.0μ  μ€μ 5.0μ ">
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                </div>

                <div class="misc">
                  <time>2021.01.01</time>
                  <span>μ€λμμ§ κ΅¬λ§€</span>
                </div>
              </div>
            </div>
          </header>

          <div class="review-card-body">
            <div class="review-image">
              <img
                src="./assets/images/img-review-01.jpg"
                alt="ν λΆλ‘ μ ννκ² λμ λ¦¬λ·° μ¬μ§"
              />
            </div>
            <p>
              μμμ€μμ μμ΄ μλ €μμ μ±μ μμ μ¬λ €μ μΈκ±Έλ‘ κ³¨λμ΅λλ€!
              μμ£Όμμ£Ό λ¨λ―νκ³  ν¬κΈ°λ μ λΉνκ³  λ―ΌνΈ μ¬κ³ μΆμμ§λ§ νμ  γ γ 
            </p>
          </div>

          <footer class="review-card-footer">
            <button class="btn-outlined btn-32" type="button">
              λμμ΄ λΌμ
            </button>

            <p>
              <strong><span>7</span>λͺ</strong>μκ² λμμ΄ λμμ΅λλ€.
            </p>
          </footer>
        </article>
      </li>

      <!-- NOTE: Button Pressed: True, Helped number β₯ 1 -->
      <li class="review-item">
        <article class="review-card">
          <header class="review-card-header">
            <h3 class="visually-hidden">νμ νμΈλΉμμΈ λμ΄ μμ±ν λ¦¬λ·°</h3>

            <a class="avatar-24" href="/">
              <img
                src="./assets/images/img-user-05.jpeg"
                alt="νμ νμΈλΉμμΈ λμ νλ‘ν μ΄λ―Έμ§"
              />
            </a>

            <div class="info">
              <a class="username" href="/"><strong>νμ νμΈλΉμμΈ</strong></a>

              <div class="detail">
                <div class="star-rating-13" aria-label="5.0μ  μ€μ 5.0μ ">
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                </div>

                <div class="misc">
                  <time>2021.01.01</time>
                  <span>μ€λμμ§ κ΅¬λ§€</span>
                </div>
              </div>
            </div>
          </header>

          <div class="review-card-body">
            <p>
              μ€λλ μννΈ νμ₯λ λ°©μ΄λΌ μΈνμ΄ λλ¬΄ μ¬ν΄ κΈνκ² κ΅¬λ§€νμ΅λλ€!
              μμ½λ°°μ‘μ΄λΌ 10μΌ κ°κΉμ΄ κΈ°λ€λ Έλλ° λλ¬΄λλ¬΄ λ§μ‘±μ€λ¬μμ~ :) λ°©μ΄
              ν° νΈμ΄λΌ μ μ²΄κ° λ€ λ°λ»ν΄μ§κΈΈ λ°λΌμ§λ μμκ³ , νκΈ°λ₯Ό λ¨Όμ 
              λ΄€λν°λΌ ν¬κ² κΈ°λλ₯Ό μνμλλ° κΈ°λ μ΄μμλλ€. νμ΄λμΌλ©΄ νμ€ν
              λ°© κ³΅κΈ°κ° λ¬λΌμ Έμ! νλ!!! κΉμ§ μλμ΄λ μ°¨κ°μ΄ κ³΅κΈ°κ°
              λ°λ»ν΄μ§λλ€~ λ§μ‘±μ€λ¬μμ!!! μ¬ κ²¨μΈ λλΆμ λ¨μ§ μκ³  λ³΄λΌ μ
              μμκ² κ°μ΅λλΉ
            </p>
          </div>

          <footer class="review-card-footer">
            <button class="btn-fill-primary btn-32" type="button">
              <i class="ic-check" aria-hidden></i>
              λμλ¨
            </button>

            <p>
              <strong><span>2</span>λͺ</strong>μκ² λμμ΄ λμμ΅λλ€.
            </p>
          </footer>
        </article>
      </li>

      <!-- NOTE: Button Pressed: False, Helped number = 0 -->
      <li class="review-item">
        <article class="review-card">
          <header class="review-card-header">
            <h3 class="visually-hidden">μΈν¬λμΌμλΌ λμ΄ μμ±ν λ¦¬λ·°</h3>

            <a class="avatar-24" href="/">
              <img
                src="./assets/images/img-user-06.jpeg"
                alt="μΈν¬λμΌμλΌ λμ νλ‘ν μ΄λ―Έμ§"
              />
            </a>

            <div class="info">
              <a class="username" href="/"><strong>μΈν¬λμΌμλΌ</strong></a>

              <div class="detail">
                <div class="star-rating-13" aria-label="5.0μ  μ€μ 5.0μ ">
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star is-active"></i>
                  <i class="ic-star"></i>
                  <i class="ic-star"></i>
                </div>

                <div class="misc">
                  <time>2021.01.01</time>
                  <span>μ€λμμ§ κ΅¬λ§€</span>
                </div>
              </div>
            </div>
          </header>

          <div class="review-card-body">
            <p>κ°κ²© λλΉ λ§μ‘±ν©λλ€.</p>
          </div>

          <footer class="review-card-footer">
            <button class="btn-outlined btn-32" type="button">
              λμμ΄ λΌμ
            </button>
          </footer>
        </article>
      </li>
    </ol>

    <div class="pagination">
      <!-- <button class="page-control page-prev">
                  <i class="ic-chevron"></i>
                </button> -->
      <ol class="page-list">
        <li class="page-item is-active">
          <a href="/">1</a>
        </li>
        <li class="page-item">
          <a href="/">2</a>
        </li>
        <li class="page-item">
          <a href="/">3</a>
        </li>
        <li class="page-item">
          <a href="/">4</a>
        </li>
        <li class="page-item">
          <a href="/">5</a>
        </li>
      </ol>
      <button class="page-control page-next">
        <i class="ic-chevron"></i>
      </button>
    </div>
  </div>
</section>
```

<br />
<br />

<!-- Todo list -->

### π Todo list

- [x] Base
  - [x] Reset & Normalise CSS
  - [x] Prepare assets
- [x] Variables
- [x] Mixins
- [x] Modules
- [ ] Components
  - [x] GNB
  - [x] Sidebar
  - [x] Search Modal
  - [x] Search History
  - [x] LNG
  - [x] Global Footer
  - [x] Breadcrumb & Product Carousel
  - [x] Product Info & Order Form
  - [x] Page Structure & Shared Components
  - [ ] π§ Product Section
  - [ ] Order Forms
  - [ ] Dialogs
- [ ] Javascript
