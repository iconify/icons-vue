<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ssxoo_jdk"/><path class="xdk4xtk9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:no-littering" /></template>
<style>
.ssxoo_jdk {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m24 30a23.9 23.9 0 0 1-5.045 14.713l-10.84-10.84h.85V23.092c0-.642-.662-1.162-1.479-1.162H27.961c-.526 0-.984.218-1.246.543l-9.427-9.428A23.9 23.9 0 0 1 32 8c13.255 0 24 10.745 24 24m-26.709-6.951l-.087-.088l.087-.707zm10.114 10.114l-1.249-1.249v-9.66zM8 32a23.9 23.9 0 0 1 5.045-14.713l12.428 12.43l-2.678 2.16v1.34l4.093-2.085l2.402 2.402v16.282h2.956l1.477-11.619l1.479 11.619h2.954v-7.417l8.556 8.557A23.9 23.9 0 0 1 32 56C18.745 56 8 45.256 8 32");
}

.xdk4xtk9t {
  fill: currentColor;
  d: path("M32.602 20.381h2.595c.956 0 1.73-.618 1.73-1.379v-3.44c0-.761-.774-1.378-1.73-1.378h-2.595c-.956 0-1.73.617-1.73 1.378v3.44c-.001.761.774 1.379 1.73 1.379M19.925 34.23h2.815v3.754h-2.815zm3.86 4.633H26.6v3.756h-2.815zm-4.623 4.283h2.816V46.9h-2.816z");
}

</style>
