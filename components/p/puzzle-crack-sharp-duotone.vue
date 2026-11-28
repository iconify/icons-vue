<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="su1uoq5-g"/><path clip-rule="evenodd" class="f13hu2bus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:puzzle-crack-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f13hu2bus {
  fill-rule: evenodd;
  d: path("M9.382 22L10.106 20.5528L11.846 17.0718L10.168 14.5547C9.944 14.2188 9.944 13.7812 10.168 13.4453L12.465 10L14.129 11.1094L12.202 14L13.832 16.4453C14.031 16.7439 14.055 17.1262 13.894 17.4472L11.894 21.4472L11.618 22H9.382Z");
}

.su1uoq5-g {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 2C12.209 2 14 3.7908 14 6H17C17.552 6 18 6.4477 18 7V10C20.209 10 22 11.7908 22 14C22 16.2092 20.209 18 18 18V21C18 21.5523 17.552 22 17 22H3C2.448 22 2 21.5523 2 21V17C2 16.4477 2.448 16 3 16H4C5.105 16 6 15.1046 6 14C6 12.8954 5.105 12 4 12H3C2.448 12 2 11.5523 2 11V7C2 6.4477 2.448 6 3 6H6C6 3.7908 7.791 2 10 2Z");
}

</style>
