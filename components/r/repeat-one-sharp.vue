<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppkigwdau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:repeat-one-sharp" /></template>
<style>
.ppkigwdau {
  fill: currentColor;
  d: path("M11.808 14.692v-4.5h-1.192v-.884h2.076v5.384zM7.308 21L4 17.692l3.308-3.307l.708.719l-2.089 2.088h11.38v-4h1v5H5.928l2.089 2.089zM5.692 10.808v-5h12.381l-2.089-2.089l.708-.719L20 6.308l-3.308 3.308l-.707-.72l2.088-2.088H6.693v4z");
}

</style>
