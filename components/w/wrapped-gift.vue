<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tro55rs-x"/><path class="ey4_hb7fc"/><path class="my5nakbhw"/><path class="rk7pxqb2t"/><path class="xawqe3sly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:wrapped-gift" /></template>
<style>
.ey4_hb7fc {
  fill: var(--svg-color--fdd888, #fdd888);
  d: path("M36 11c0 2.2-1.8 4-4 4H4c-2.2 0-4-1.8-4-4s1.8-4 4-4h28c2.2 0 4 1.8 4 4");
}

.my5nakbhw {
  fill: var(--svg-color--fcab40, #fcab40);
  d: path("M3 15h30v2H3z");
}

.rk7pxqb2t {
  fill: var(--svg-color--da2f47, #da2f47);
  d: path("M19 3h-2a3 3 0 0 0-3 3v29h8V6a3 3 0 0 0-3-3");
}

.tro55rs-x {
  fill: var(--svg-color--fdd888, #fdd888);
  d: path("M33 31c0 2.2-1.8 4-4 4H7c-2.2 0-4-1.8-4-4V14c0-2.2 1.8-4 4-4h22c2.2 0 4 1.8 4 4z");
}

.xawqe3sly {
  fill: var(--svg-color--da2f47, #da2f47);
  d: path("M16 7c1.1 0 1.263-.516.361-1.147L9.639 1.147a1.795 1.795 0 0 0-2.631.589L4.992 5.264C4.446 6.219 4.9 7 6 7zm4 0c-1.1 0-1.263-.516-.361-1.147l6.723-4.706a1.796 1.796 0 0 1 2.631.589l2.016 3.527C31.554 6.219 31.1 7 30 7z");
}

</style>
