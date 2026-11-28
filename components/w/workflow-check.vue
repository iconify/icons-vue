<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxctg1blt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxctg1blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:workflow-check" /></template>
