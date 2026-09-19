<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc64tebsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="mc64tebsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:underline" /></template>
