<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdw90cclc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdw90cclc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:pine-tree-variant-outline" /></template>
