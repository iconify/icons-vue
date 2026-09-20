<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmkzztiqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-right-alt-outline-sharp" /></template>
<style>
.hmkzztiqm {
  fill: currentColor;
  d: path("M9.5 16.5q-1.864 0-3.182-1.318T5 12t1.318-3.182T9.5 7.5q1.748 0 3.005 1.138t1.472 2.862h5.102l-2.094-2.1l.707-.708L21 12l-3.308 3.308l-.713-.708l2.1-2.1h-5.102q-.215 1.725-1.472 2.863T9.5 16.5m2.48-2.02Q13 13.463 13 12t-1.02-2.48T9.5 8.5T7.02 9.52T6 12t1.02 2.48T9.5 15.5t2.48-1.02M9.5 12");
}

</style>
