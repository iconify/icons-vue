<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwpuokbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwpuokbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:undo" /></template>
