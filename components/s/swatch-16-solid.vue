<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3nm04bma.css';
import '../../css/k/khhbi52zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a3nm04bma"/><path class="khhbi52zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:swatch-16-solid" /></template>
