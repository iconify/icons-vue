<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us55s7bkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="us55s7bkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:subtract-large" /></template>
