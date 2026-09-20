<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru1stbp4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ru1stbp4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:stratovolcano-lava" /></template>
