<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ordbaybav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ordbaybav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:transform-code" /></template>
