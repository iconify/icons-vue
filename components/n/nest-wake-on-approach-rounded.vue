<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_q6nlb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-wake-on-approach-rounded" /></template>
<style>
.v_q6nlb7p {
  fill: currentColor;
  d: path("M19.207 11.12q-.265-.264-.265-.62V5.308q0-.356.265-.62t.62-.265t.62.265t.265.62V10.5q0 .356-.265.62q-.264.265-.62.265t-.62-.265m-11.33-.612Q7 9.63 7 8.385t.877-2.123T10 5.385t2.123.877T13 8.385t-.877 2.123t-2.123.877t-2.123-.877M3 18.616v-1.647q0-.638.367-1.168t.964-.828q1.346-.634 2.766-.996q1.42-.361 2.903-.361t2.903.361t2.766.996q.597.298.964.828T17 16.969v1.646z");
}

</style>
