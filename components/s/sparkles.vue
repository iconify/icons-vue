<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="yzqknwyen"/><path class="ksstb6azw"/><path class="n11yc9b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:sparkles" /></template>
<style>
.ksstb6azw {
  fill: var(--svg-color--6adbc6, #6adbc6);
  d: path("M53 0c0 8.4-4.6 16-11 16c6.4 0 11 7.6 11 16c0-8.4 4.6-16 11-16c-6.4 0-11-7.6-11-16");
}

.n11yc9b2c {
  fill: var(--svg-color--ff73c0, #ff73c0);
  d: path("M48 32c0 8.4-4.6 16-11 16c6.4 0 11 7.6 11 16c0-8.4 4.6-16 11-16c-6.4 0-11-7.6-11-16");
}

.yzqknwyen {
  fill: var(--svg-color--ffe54d, #ffe54d);
  d: path("M22 0c0 16.9-9.1 32-22 32c12.9 0 22 15.1 22 32c0-16.9 9.1-32 22-32c-12.9 0-22-15.1-22-32");
}

</style>
