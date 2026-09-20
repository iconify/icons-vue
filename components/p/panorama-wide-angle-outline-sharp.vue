<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey67rxmav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:panorama-wide-angle-outline-sharp" /></template>
<style>
.ey67rxmav {
  fill: currentColor;
  d: path("M7.732 18.788q-2.032-.213-3.924-.672q-.43-1.495-.618-3.02Q3 13.568 3 12t.19-3.095t.618-3.02q1.84-.443 3.863-.664T12 5t4.329.221t3.863.664q.43 1.494.619 3.02T21 12t-.192 3.095t-.616 3.02q-1.892.46-3.924.673T12 19t-4.268-.213m8.128-.969q1.83-.181 3.54-.568q.325-1.3.463-2.6T20 12t-.137-2.65t-.463-2.6q-1.663-.375-3.485-.562Q14.092 6 12 6q-2.086 0-3.909.188q-1.822.187-3.491.562q-.325 1.3-.462 2.6T4 12t.138 2.65t.462 2.6q1.71.387 3.54.568Q9.972 18 12 18t3.86-.182");
}

</style>
