<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="m9b77pbab"/><path class="hm28yvgss"/><path class="ccmyxx8tw"/><path class="hsbs6im3y"/><path class="hlc4aub2b"/><path class="o3jikqbtg"/><path class="xa7_xeb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:military-helmet" /></template>
<style>
.ccmyxx8tw {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M18 33.966C8.733 33.966 4.034 29.94 4.034 22S8.733 10.034 18 10.034c9.268 0 13.966 4.026 13.966 11.966S27.268 33.966 18 33.966m0-22C9.79 11.966 5.966 15.154 5.966 22S9.79 32.034 18 32.034S30.034 28.846 30.034 22S26.21 11.966 18 11.966");
}

.hlc4aub2b {
  fill: var(--svg-color--717735, #717735);
  d: path("M33 15c-.987-7.586-4.602-14-15-14S3.987 7.414 3 15c-.152 1.169-2 2-2 6c0 2 1.366 3.564 3 4c0-4 0-8 14-8s14 4 14 8c1.634-.436 3-2 3-4c0-4-1.848-4.831-2-6");
}

.hm28yvgss {
  fill: var(--svg-color--383a18, #383a18);
  d: path("M18 15.068C7.602 15.068 2.001 17 2.001 21c0 2 .365-.176 1.999.261c3.105.829 3-2.317 14-2.317s10.895 3.146 14 2.317c1.634-.437 1.999 1.739 1.999-.261c0-4-5.601-5.932-15.999-5.932");
}

.hsbs6im3y {
  fill: var(--svg-color--662113, #662113);
  d: path("M24 32c0 1.657-2.686 3-6 3s-6-1.343-6-3s2.686-1 6-1s6-.657 6 1");
}

.m9b77pbab {
  fill: var(--svg-color--464f25, #464f25);
  d: path("M33 15c-.987-7.586-4.602-14-15-14S3.987 7.414 3 15c-.152 1.169-2 2-2 6c0 2 1.366 3.564 3 4c3.105.829 3-1 14-1s10.895 1.829 14 1c1.634-.436 3-2 3-4c0-4-1.848-4.831-2-6");
}

.o3jikqbtg {
  fill: var(--svg-color--a3a364, #a3a364);
  d: path("M18 13c-7 0-17 1-17 8c0 2 1.366 3.564 3 4c0-4 0-8 14-8s14 4 14 8c1.634-.436 3-2 3-4c0-7-11-8-17-8");
}

.xa7_xeb4y {
  fill: var(--svg-color--677032, #677032);
  d: path("M18 16C7.602 16 1 17 1 21c0 2 1.366 3.564 3 4c0-4 0-8 14-8s14 4 14 8c1.634-.436 3-2 3-4c0-4-6.602-5-17-5");
}

</style>
