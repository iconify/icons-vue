<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tow-1j04m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="tow-1j04m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:tooltip-end-text" /></template>
