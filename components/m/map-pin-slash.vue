<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo2uy2bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jo2uy2bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:map-pin-slash" /></template>
