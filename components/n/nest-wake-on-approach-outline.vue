<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxd-kfa5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-wake-on-approach-outline" /></template>
<style>
.uxd-kfa5h {
  fill: currentColor;
  d: path("M19.207 11.12q-.265-.264-.265-.62V5.308q0-.356.265-.62t.62-.265t.62.265t.265.62V10.5q0 .356-.265.62q-.264.265-.62.265t-.62-.265m-11.33-.612Q7 9.63 7 8.385t.877-2.123T10 5.385t2.123.877T13 8.385t-.877 2.123t-2.123.877t-2.123-.877M3 18.616v-1.647q0-.638.367-1.168t.964-.828q1.346-.634 2.766-.996q1.42-.361 2.903-.361t2.903.361t2.766.996q.597.298.964.828T17 16.969v1.646zm1-1h12v-.647q0-.371-.23-.653q-.232-.283-.578-.466q-1.217-.611-2.518-.923T10 14.616t-2.674.311t-2.518.923q-.346.183-.577.466q-.231.282-.231.653zm7.413-7.819Q12 9.21 12 8.385t-.587-1.413T10 6.385t-1.412.587T8 8.385t.588 1.412t1.412.588t1.413-.588M10 17.616");
}

</style>
