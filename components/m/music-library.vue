<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc6c15taa.css';
import '../../css/p/pnnjfds4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gc6c15taa"/><path class="pnnjfds4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:music-library" /></template>
