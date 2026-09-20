<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g34get5ca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g34get5ca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vertical-rotate-clockwise" /></template>
