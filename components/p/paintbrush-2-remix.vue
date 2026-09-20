<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nujijkimx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nujijkimx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:paintbrush-2-remix" /></template>
