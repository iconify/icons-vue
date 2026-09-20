<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nyoim6mcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="nyoim6mcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:windrose" /></template>
