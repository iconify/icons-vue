<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiuhgcbqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiuhgcbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:numba" /></template>
