<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvxr66big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvxr66big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:music-note-whole" /></template>
