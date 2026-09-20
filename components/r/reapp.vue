<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":338};
const content = `<path class="f470yjnvk"/><path class="wl_yg2cqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:reapp" /></template>
<style>
.f470yjnvk {
  fill: var(--svg-color--27ccf5, #27ccf5);
  d: path("M63.512.566S.23.566.23 63.85v221.486s63.283 1.265 63.283-62.332V79.667c0-8.738 7.084-15.818 15.818-15.818h46.831C187.545 63.85 188.81.566 188.81.566z");
}

.wl_yg2cqh {
  fill: var(--svg-color--22e071, #22e071);
  d: path("M192.026 114.941v143.332c0 8.738-7.084 15.818-15.818 15.818h-46.826c-61.384 0-62.653 63.283-62.653 63.283h125.297s63.283 0 63.283-63.283V52.605s-63.283-1.264-63.283 62.336");
}

</style>
