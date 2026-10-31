<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/riy76el_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="riy76el_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:music-notes-round" /></template>
