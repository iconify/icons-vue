<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kq6ptrbxl"/><path class="xalju1bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-install-desktop" /></template>
<style>
.kq6ptrbxl {
  fill: currentColor;
  d: path("M20 17H4V5h8V3H4c-1.1 0-2 .9-2 2v12a2 2 0 0 0 2 2h4v1c0 .55.45 1 1 1h6c.55 0 1-.45 1-1v-1h4c1.1 0 2-.9 2-2v-3h-2z");
}

.xalju1bab {
  fill: currentColor;
  d: path("M17.71 13.29L21.3 9.7a.996.996 0 1 0-1.41-1.41L18 10.17V4c0-.55-.45-1-1-1s-1 .45-1 1v6.17l-1.89-1.88A.996.996 0 1 0 12.7 9.7l3.59 3.59c.4.39 1.03.39 1.42 0");
}

</style>
