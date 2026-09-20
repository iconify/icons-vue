<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxo7yvj2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:smart-outlet-sharp" /></template>
<style>
.rxo7yvj2z {
  fill: currentColor;
  d: path("M7 13h2V9H7zm4 4h2v-1q0-.45-.275-.725T12 15t-.725.275T11 16zm4-4h2V9h-2zm-3 9q-2.075 0-3.9-.788t-3.175-2.137T2.788 15.9T2 12t.788-3.9t2.137-3.175T8.1 2.788T12 2t3.9.788t3.175 2.137T21.213 8.1T22 12t-.788 3.9t-2.137 3.175t-3.175 2.138T12 22");
}

</style>
