<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_x5ixsem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d_x5ixsem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:star" /></template>
