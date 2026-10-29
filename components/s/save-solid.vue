<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrtfb8xyf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrtfb8xyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:save-solid" /></template>
