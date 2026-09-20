<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="jsh-x--nf"/><path class="h7h72dbdn"/><path class="xmdbw975z"/><path class="xyel3_5ql"/><path class="mq4vzdbfv"/><path class="s07ij5u0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:t-shirt" /></template>
<style>
.h7h72dbdn {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M1 4.717C.352 5.088 0 5.565 0 6c0 2 1 7 2 9c.281.562 1.039.777 2 .85C3 13 2 9 1 4.717");
}

.jsh-x--nf {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M11 2C8 2 0 4 0 6s1 7 2 9s8 0 9-1s2-12 0-12");
}

.mq4vzdbfv {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M25 2h-1.068C23.515 3.695 21.021 5 18 5s-5.515-1.305-5.932-3H11C8.791 2 6 3.791 6 6c0 0 0 20-1 24s1.791 4 4 4h18c2.209 0 5 0 4-4S30 6 30 6c0-2.209-2.791-4-5-4");
}

.s07ij5u0q {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M18 7c3.866 0 7-2.239 7-5h-1.068C23.515 3.695 21.021 5 18 5s-5.515-1.305-5.932-3H11c0 2.761 3.134 5 7 5");
}

.xmdbw975z {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M25 2c3 0 11 2 11 4s-1 7-2 9s-8 0-9-1s-2-12 0-12");
}

.xyel3_5ql {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M35 4.717c.648.371 1 .848 1 1.283c0 2-1 7-2 9c-.281.562-1.039.777-2 .85C33 13 34 9 35 4.717");
}

</style>
