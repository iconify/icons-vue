<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz948sdil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz948sdil primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:tally-1-duotone" /></template>
