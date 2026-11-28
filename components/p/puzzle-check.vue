<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fd28hob_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd28hob_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:puzzle-check" /></template>
