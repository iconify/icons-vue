<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrrb-bc5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:swipe-right-2-sharp" /></template>
<style>
.mrrb-bc5a {
  fill: currentColor;
  d: path("M2 7q.75-2.65 3.55-4.325T12 1q2.35 0 4.525.775t3.975 2.25V2H22v5h-5V5.5h2.9q-1.65-1.45-3.675-2.225T12 2.5q-2.95 0-5.213 1.2T3.575 7zm8.575 15L4.6 16l1.575-1.625l2.825.8V6h2v8h1v-4h2v4h1v-3h2v3h1v-1h2v9z");
}

</style>
