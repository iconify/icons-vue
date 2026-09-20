<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dw7p0cfwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="dw7p0cfwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:remove-circle" /></template>
