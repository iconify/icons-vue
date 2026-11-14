<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cem9pvbyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-edit-32-light" /></template>
<style>
.cem9pvbyk {
  fill: currentColor;
  d: path("M25.572 16.35a2.88 2.88 0 0 1 4.144.057a2.883 2.883 0 0 1-.072 4.018l-8.609 8.543c-.351.349-.79.597-1.27.72l-3.019.779a1 1 0 0 1-1.217-1.22l.79-3.052a2.66 2.66 0 0 1 .686-1.205zM21.461 3.003a.5.5 0 0 1 .118.004a4.5 4.5 0 0 1 2.946 1.312l3.157 3.157A4.5 4.5 0 0 1 29 10.657v3.564a4.4 4.4 0 0 0-1-.205v-3.359c0-.928-.369-1.819-1.025-2.475l-3.157-3.157A3.5 3.5 0 0 0 22 4.062V9.5a2.5 2.5 0 0 1-2.5 2.5h-8A2.5 2.5 0 0 1 9 9.5V4H7.5A3.5 3.5 0 0 0 4 7.5v17a3.5 3.5 0 0 0 3 3.465V18.5A2.5 2.5 0 0 1 9.5 16h13c.384 0 .746.089 1.07.243l-.779.785A1.5 1.5 0 0 0 22.5 17h-13A1.5 1.5 0 0 0 8 18.5V28h6.308l-.226.871q-.016.064-.028.129H7.5A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3h13.843l.118.002M10 9.5a1.5 1.5 0 0 0 1.5 1.5h8A1.5 1.5 0 0 0 21 9.5V4H10z");
}

</style>
