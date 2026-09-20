<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9rlqrg6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9rlqrg6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:note-plus" /></template>
