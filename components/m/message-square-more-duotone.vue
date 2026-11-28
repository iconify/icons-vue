<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kyrppnatc"/><path clip-rule="evenodd" class="y_ejlk4cj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-more-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kyrppnatc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2H18C20.2091 2 22 3.791 22 6V14C22 16.209 20.2091 18 18 18H7.4142L3.7071 21.707C3.5196 21.895 3.2652 22 3 22C2.4477 22 2 21.552 2 21V6C2 3.791 3.7909 2 6 2Z");
}

.y_ejlk4cj {
  fill-rule: evenodd;
  d: path("M7.3333 8.667C8.0697 8.667 8.6666 9.264 8.6666 10C8.6666 10.736 8.0697 11.333 7.3333 11.333C6.5969 11.333 6 10.736 6 10C6 9.264 6.5969 8.667 7.3333 8.667ZM12 8.667C12.7364 8.667 13.3333 9.264 13.3333 10C13.3333 10.736 12.7364 11.333 12 11.333C11.2636 11.333 10.6667 10.736 10.6667 10C10.6667 9.264 11.2636 8.667 12 8.667ZM16.6667 8.667C17.4031 8.667 18 9.264 18 10C18 10.736 17.4031 11.333 16.6667 11.333C15.9303 11.333 15.3334 10.736 15.3334 10C15.3334 9.264 15.9303 8.667 16.6667 8.667Z");
}

</style>
