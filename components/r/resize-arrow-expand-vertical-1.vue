<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-1elsbgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-1elsbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:resize-arrow-expand-vertical-1" /></template>
