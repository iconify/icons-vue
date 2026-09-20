<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg47dm5zr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rg47dm5zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:shrink" /></template>
