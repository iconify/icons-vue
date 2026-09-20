<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs0j5rbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="cs0j5rbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:spiral-shape-remix" /></template>
