<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g transform="scale(.99878)"><circle class="vpn2tp30j"/><path class="w5iho-bwo"/><path class="nvobx_87x"/><path class="lkaf7s-0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:two-thirty" /></template>
<style>
.lkaf7s-0b {
  fill: var(--svg-color--788288, #788288);
  d: path("M43.45 20.08c1.143-.875 2.585-.919 3.221-.091s.229 2.216-.912 3.091l-12.11 9.315c-1.139.876-2.583.916-3.218.087c-.638-.826-.23-2.21.91-3.089l12.11-9.313");
}

.nvobx_87x {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M33.92 53.02c0 1.44-.85 2.606-1.893 2.606s-1.893-1.166-1.893-2.606V31.91c0-1.443.849-2.609 1.893-2.609c1.043 0 1.893 1.166 1.893 2.609z");
}

.vpn2tp30j {
  cx: 32.04px;
  cy: 32.04px;
  r: 29.68px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

.w5iho-bwo {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M32.04 0C14.374 0 0 14.372 0 32.04c0 17.666 14.374 32.04 32.04 32.04s32.04-14.372 32.04-32.04S49.708 0 32.04 0m0 57.843c-14.228 0-25.803-11.575-25.803-25.803S17.812 6.237 32.04 6.237c14.226 0 25.801 11.575 25.801 25.803S46.266 57.843 32.04 57.843");
}

</style>
