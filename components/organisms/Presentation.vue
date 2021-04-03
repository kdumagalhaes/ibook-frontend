<template>
  <div class="presentation">
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, ducimus
      dolore earum fugit nulla, molestias praesentium expedita, eligendi
      voluptatum provident debitis cupiditate. Aliquam provident tempora
      dignissimos itaque consequatur consectetur dolore!
    </p>

    <img src="@/assets/img/presentation.svg" alt="Apresentação" />
  </div>
</template>

<style lang="scss" scoped>
.presentation {
  display: grid;
  grid-template-columns: repeat(2, 1fr);
  grid-gap: 2rem;
  align-items: center;
  @include screen('small', 'medium') {
    grid-template-columns: 1fr;
  }
  p {
    line-height: 26px;
  }
  img {
    max-width: 100%;
  }
}
</style>
