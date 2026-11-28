<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrjpgacjo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrjpgacjo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:workflow-clock" /></template>
