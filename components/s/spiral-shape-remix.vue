<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zm03u66vf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zm03u66vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:spiral-shape-remix" /></template>
