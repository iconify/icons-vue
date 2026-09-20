<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_nc4u1cd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j_nc4u1cd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:pyramid-shape-solid" /></template>
