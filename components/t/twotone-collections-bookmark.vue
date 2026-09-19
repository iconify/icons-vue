<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ufmn8f6-m"/><path class="yqwuuybhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-collections-bookmark" /></template>
<style>
.ufmn8f6-m {
  fill: currentColor;
  d: path("M20 4h-1v9l-3-2.25L13 13V4H8v12h12z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.yqwuuybhp {
  fill: currentColor;
  d: path("M4 22h14v-2H4V6H2v14c0 1.1.9 2 2 2m18-6V4c0-1.1-.9-2-2-2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2M15 4h2v5l-1-.75L15 9zM8 4h5v9l3-2.25L19 13V4h1v12H8z");
}

</style>
