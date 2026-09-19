<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9vdr7-qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9vdr7-qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:number-5-bold" /></template>
