<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":368};
const content = `<path class="oynqdsb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:stackblitz-icon" /></template>
<style>
.oynqdsb-h {
  fill: var(--svg-color--49a2f8, #49a2f8);
  d: path("M109.586 217.013H0L200.34 0l-53.926 150.233H256L55.645 367.246l53.927-150.233z");
}

</style>
