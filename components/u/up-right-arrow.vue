<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="f0coyab8t"/><path class="f6chwabuy"/><path class="fvegjvbtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:up-right-arrow" /></template>
<style>
.f0coyab8t {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M0 32a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V4a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4z");
}

.f6chwabuy {
  fill: var(--svg-color--fff, #fff);
  d: path("M27 25V9H11z");
}

.fvegjvbtt {
  fill: var(--svg-color--fff, #fff);
  d: path("M7 23.343L19.816 10.53l5.656 5.657L12.657 29z");
}

</style>
