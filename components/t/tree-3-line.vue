<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulhwzkxmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulhwzkxmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-3-line" /></template>
