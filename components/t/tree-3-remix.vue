<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldqzqcgzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ldqzqcgzf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:tree-3-remix" /></template>
