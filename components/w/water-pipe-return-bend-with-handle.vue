<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isaurbc7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="isaurbc7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:water-pipe-return-bend-with-handle" /></template>
