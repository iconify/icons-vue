<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0gym56-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p0gym56-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:pencil-square-solid" /></template>
