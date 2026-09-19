<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ils3d3b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ils3d3b0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:window-16-solid" /></template>
