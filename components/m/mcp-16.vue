<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v545msb3x.css';
import '../../css/i/izcv4zh7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v545msb3x"/><path class="izcv4zh7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:mcp-16" /></template>
