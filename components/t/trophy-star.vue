<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ndwtwom7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ndwtwom7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:trophy-star" /></template>
