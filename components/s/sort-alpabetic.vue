<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/csvt9dbkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csvt9dbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:sort-alpabetic" /></template>
