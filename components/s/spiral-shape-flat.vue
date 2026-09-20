<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kuksvtbaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kuksvtbaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex-color:spiral-shape-flat" /></template>
