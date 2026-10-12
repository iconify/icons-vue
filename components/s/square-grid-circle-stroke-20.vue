<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5lejhb4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p5lejhb4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:square-grid-circle-stroke-20" /></template>
