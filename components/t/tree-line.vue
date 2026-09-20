<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i--t4vbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i--t4vbcf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-line" /></template>
