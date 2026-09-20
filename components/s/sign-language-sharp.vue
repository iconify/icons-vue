<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlx8h1fid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sign-language-sharp" /></template>
<style>
.xlx8h1fid {
  fill: currentColor;
  d: path("m11.433 22l-8.727-.779l.123-1l3.975.34l.706-2.507l-5.627-1.063l.177-.989l5.725 1.089l.656-2.322l-6.489-1.748l.3-.944l6.464 1.729l.625-2.21l-4.504-2.304l.496-.876l6.634 3.428l.125-3.013l1.397-.308l2.607 5.073q.2.379.216.793q.015.413-.11.798l-1.218 4.375q-.317 1.169-1.324 1.866T11.433 22m6.73-7.139q.03-.286.023-.578t-.09-.58l-2.982-5.759l1.42-.734l-2.053-4.927l.921-.404l2.867 6.89l2.11-2.34l1.388.748l-1.451 5.58q-.112.405-.345.73q-.232.327-.58.544zM8.706 8.025L7.223 6.273l.762-.634l2.298 2.734l-.012.475zm3.583-1.27l-2.431-3.49l.829-.592l2.732 3.952z");
}

</style>
