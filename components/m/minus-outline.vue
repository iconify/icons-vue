<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di5cigt5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="minus-outline"><path class="Vector di5cigt5f" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:minus-outline" /></template>
