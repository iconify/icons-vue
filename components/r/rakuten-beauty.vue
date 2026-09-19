<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="m9jzk0blu"/><path class="y457ft69j"/></g><path class="jgzfsab6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-beauty" /></template>
<style>
.jgzfsab6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.922 5.524h8.256c2.05 0 3.701 1.65 3.701 3.7v29.248M29.922 24.694h11.957m-11.957-12.78h11.957m-11.957 6.39h11.957");
}

.m9jzk0blu {
  d: path("M20.172 35.215a4.273 4.273 0 1 1 4.273 4.272c-2.36 0-4.057-1.922-4.273-4.272L17.42 5.5l-2.752 29.715c-.217 2.35-1.914 4.272-4.274 4.272a4.273 4.273 0 1 1 4.274-4.272");
}

.y457ft69j {
  d: path("M6.595 42.5c1.045-.464 2.176-1.936 2.327-3.276");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
