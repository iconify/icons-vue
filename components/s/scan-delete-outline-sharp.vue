<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlr4wlb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:scan-delete-outline-sharp" /></template>
<style>
.mlr4wlb7m {
  fill: currentColor;
  d: path("M6 4v4zv16zM5 21V3h9.5L19 7.5v4.812q-.238-.06-.488-.09t-.512-.03V8h-4V4H6v16h6.446q.085.28.212.524q.127.243.296.476zm10.9-.134l-.688-.689l2.1-2.1l-2.1-2.1l.688-.689l2.1 2.1l2.1-2.1l.689.689l-2.075 2.1l2.075 2.1l-.689.689L18 18.79z");
}

</style>
