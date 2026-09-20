<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gstmttb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:symptoms" /></template>
<style>
.gstmttb6e {
  fill: currentColor;
  d: path("M18.276 20.27q-1.259 0-2.123-.878q-.864-.876-.87-2.126q0-.616.253-1.174q.254-.557.72-.998l2.013-1.902l2.008 1.9q.446.424.707.988t.266 1.178q-.02 1.258-.877 2.134q-.857.877-2.097.877m-8.188-6.856Q9.3 12.625 9.3 11.5t.788-1.912T12 8.8t1.913.788t.787 1.912t-.787 1.913T12 14.2t-1.912-.787M11.992 18q-3.247 0-5.916-1.768T2.078 11.5q1.33-2.964 4.001-4.732T11.998 5t5.921 1.768t4.004 4.732q-.15.334-.312.645t-.363.601L18.223 9.93l-2.734 2.611q.082-.251.123-.508t.042-.532q0-1.522-1.067-2.588t-2.592-1.066T9.41 8.913t-1.063 2.592t1.066 2.586q1.065 1.063 2.588 1.063q.408 0 .79-.079q.381-.079.731-.261q-.396.73-.563 1.543t-.018 1.619q-.236.024-.47.024z");
}

</style>
