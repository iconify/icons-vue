<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsc0xs_ii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsc0xs_ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:pine-tree-star" /></template>
