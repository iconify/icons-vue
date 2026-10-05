<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l8ac42biz"/><path class="v58r6i8tq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-2-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.l8ac42biz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 5C16.6569 5 18 6.34312 18 8V16C18 17.6569 16.6569 19 15 19H4C2.34312 19 1 17.6569 1 16V8C1 6.34312 2.34312 5 4 5H15Z");
}

.v58r6i8tq {
  d: path("M20.1055 7.32934C21.4351 6.66467 22.9998 7.63183 23 9.11841V14.8831C22.9995 16.3694 21.435 17.3357 20.1055 16.6711L16.5527 14.8948C16.2141 14.7254 16.0001 14.3788 16 14.0002V10.0002C16.0002 9.62176 16.2143 9.27608 16.5527 9.10669L20.1055 7.32934Z");
}

</style>
