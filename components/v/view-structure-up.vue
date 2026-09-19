<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxq501boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxq501boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:view-structure-up" /></template>
