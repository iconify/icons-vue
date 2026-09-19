<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxm3opmuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nxm3opmuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:undo" /></template>
