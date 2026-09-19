<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm0tk8bew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sparks-outline"><path class="Vector gm0tk8bew" clip-rule="evenodd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:sparks-outline" /></template>
