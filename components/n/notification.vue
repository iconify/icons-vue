<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/duxymcc3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="duxymcc3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:notification" /></template>
