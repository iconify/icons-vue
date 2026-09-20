<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uv313ccnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uv313ccnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pine-tree-remix" /></template>
