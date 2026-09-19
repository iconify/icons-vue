<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euokmho5h"/><path class="feui3y4kq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-install-mobile" /></template>
<style>
.euokmho5h {
  fill: currentColor;
  d: path("M18.71 13.29L22.3 9.7a.996.996 0 1 0-1.41-1.41L19 10.17V4c0-.55-.45-1-1-1s-1 .45-1 1v6.17l-1.89-1.88A.996.996 0 1 0 13.7 9.7l3.59 3.59c.4.39 1.03.39 1.42 0");
}

.feui3y4kq {
  fill: currentColor;
  d: path("M17 18H7V6h7V1H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2v-5h-2z");
}

</style>
