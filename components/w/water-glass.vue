<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlu4xcbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlu4xcbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:water-glass" /></template>
