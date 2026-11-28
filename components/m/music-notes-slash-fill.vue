<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8x6d_bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="x8x6d_bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:music-notes-slash-fill" /></template>
