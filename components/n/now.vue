<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":233};
const content = `<path class="jq6gtxb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:now" /></template>
<style>
.jq6gtxb6m {
  d: path("M128.1 0L0 232.153h256L128.1 0zm-10.876 46.875l93.256 171.943H22.559l94.665-171.943z");
  fill: var(--svg-color--000, #000);
}

</style>
