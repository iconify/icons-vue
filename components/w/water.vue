<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svgx0q8ik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="svgx0q8ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:water" /></template>
