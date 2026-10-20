<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/piznlmb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piznlmb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:pencil-ruler" /></template>
