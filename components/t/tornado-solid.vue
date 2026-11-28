<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3_50rzgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3_50rzgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tornado-solid" /></template>
