<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="c6ydxhbbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-symbol-28-regular" /></template>
<style>
.c6ydxhbbm {
  fill: currentColor;
  d: path("M12.984 3.404a.75.75 0 1 0-1.468-.308L10.28 9H3.75a.75.75 0 0 0 0 1.5h6.216L8.606 17H2.75a.75.75 0 1 0 0 1.5h5.542l-1.276 6.096a.75.75 0 1 0 1.468.308l1.34-6.404h6.468l-1.276 6.096a.75.75 0 0 0 1.468.308l1.34-6.404h6.426a.75.75 0 0 0 0-1.5h-6.112l1.36-6.5h5.752a.75.75 0 0 0 0-1.5h-5.437l1.171-5.596a.75.75 0 1 0-1.468-.308L18.28 9h-6.467zM16.606 17h-6.468l1.36-6.5h6.468z");
}

</style>
