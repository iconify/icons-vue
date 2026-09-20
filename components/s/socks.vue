<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="q5jqgmb8v"/><path class="qxw14nbao"/><path class="pw9xtxb8p"/><path class="d2bxf-btu"/><path class="cejwgj5-f"/><path class="bw59rwvnt"/><path class="keqrayb3m"/><path class="dz8qw4iwg"/><path class="sbqp8ccxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:socks" /></template>
<style>
.bw59rwvnt {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M23.676 34.682a4.5 4.5 0 0 1-6.364-6.364s1.149.133 3.69 2.674s2.674 3.69 2.674 3.69M18 0h-5c-1.1 0-2 .9-2 2v2h9V2c0-1.1-.9-2-2-2");
}

.cejwgj5-f {
  fill: var(--svg-color--1c6399, #1c6399);
  d: path("m10.994 18.999l.006-16l9 .003l-.006 16z");
}

.d2bxf-btu {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M30 4h-5c-1.1 0-2 .9-2 2v2h9V6c0-1.1-.9-2-2-2M15 15.276c-.983 0-1.893.294-2.667.784v4.549h-2.3c.175 2.603 2.319 4.667 4.966 4.667a5 5 0 0 0 5-5v-5z");
}

.dz8qw4iwg {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M11.676 30.682a4.5 4.5 0 0 1-6.364-6.364s1.149.133 3.69 2.674s2.674 3.69 2.674 3.69");
}

.keqrayb3m {
  fill: var(--svg-color--1c6399, #1c6399);
  d: path("m12.202 17.451l6.354 6.354l-6.878 6.878l-6.354-6.354z");
}

.pw9xtxb8p {
  fill: var(--svg-color--1c6399, #1c6399);
  d: path("m24.202 21.451l6.354 6.354l-6.878 6.878l-6.354-6.354z");
}

.q5jqgmb8v {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M27 19.276c-.983 0-1.893.294-2.667.784v4.549h-2.3c.175 2.603 2.319 4.667 4.966 4.667a5 5 0 0 0 5-5v-5z");
}

.qxw14nbao {
  fill: var(--svg-color--1c6399, #1c6399);
  d: path("m22.995 22.999l.005-16l9 .003l-.005 16z");
}

.sbqp8ccxl {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M22.994 10.067h9v2h-9zm0 4h9v2h-9zm-12-8h9v2h-9zm0 4h9v2h-9z");
}

</style>
