<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fka7ssbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="menu-outline"><path class="(Stroke) 38 Vector fka7ssbnm" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:menu-outline" /></template>
