<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_l8wibur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_l8wibur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:square-dashed-text" /></template>
