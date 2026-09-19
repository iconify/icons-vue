<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bm-9v2lvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bm-9v2lvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:mcp" /></template>
