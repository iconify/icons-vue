<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9474b_xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:music-cast-sharp" /></template>
<style>
.n9474b_xp {
  fill: currentColor;
  d: path("M12.089 18.123q-.877-.877-.877-2.123t.88-2.123t2.12-.877q.575 0 1.091.205t.909.614V4.692h4.884V7h-3.884v9q0 1.238-.877 2.119T14.212 19t-2.123-.877M2.903 16q0-2.34.892-4.393q.893-2.053 2.431-3.591t3.597-2.432t4.388-.892v1q-2.108 0-3.99.812T6.934 8.72t-2.218 3.273T3.904 16zm4.154 0q0-1.477.57-2.784t1.542-2.28t2.27-1.531t2.772-.559v1q-2.558 0-4.356 1.795T8.058 16z");
}

</style>
