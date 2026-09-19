<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dj38i64xy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:white-exclamation-mark" /></template>
<style>
.dj38i64xy {
  fill: currentColor;
  d: path("m38.792 4l-3.614 36.439h-6.356L25.208 4zM41 2H23l4.01 40.439h9.979zm-9 46.707c3.122 0 5.662 2.533 5.662 5.646S35.122 60 32 60c-3.123 0-5.664-2.533-5.664-5.646s2.541-5.647 5.664-5.647m0-2c-4.233 0-7.664 3.424-7.664 7.646S27.767 62 32 62s7.662-3.424 7.662-7.646s-3.43-7.647-7.662-7.647");
}

</style>
