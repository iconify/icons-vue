<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mcp9m9fsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mcp9m9fsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:telescope" /></template>
