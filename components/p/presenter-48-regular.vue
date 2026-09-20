<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a9jbabs5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presenter-48-regular" /></template>
<style>
.a9jbabs5i {
  fill: currentColor;
  d: path("M40.75 23a1.25 1.25 0 0 1 .883 2.134L31 35.768v3.982A4.25 4.25 0 0 1 26.75 44h-5.5A4.25 4.25 0 0 1 17 39.75v-3.982L6.366 25.134A1.25 1.25 0 0 1 7.25 23zM19.134 34.366c.234.235.366.553.366.884v4.5c0 .966.783 1.75 1.75 1.75h5.5a1.75 1.75 0 0 0 1.75-1.75v-4.5c0-.331.132-.65.366-.884l8.866-8.866H10.267zM27.25 16a4.25 4.25 0 0 1 4.25 4.25V21H29v-.75a1.75 1.75 0 0 0-1.75-1.75h-6.5A1.75 1.75 0 0 0 19 20.25V21h-2.5v-.75A4.25 4.25 0 0 1 20.75 16zM24 4a5 5 0 1 1 0 10a5 5 0 0 1 0-10m0 2.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5");
}

</style>
