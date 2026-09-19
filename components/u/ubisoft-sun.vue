<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihikl0b1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ihikl0b1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ubisoft-sun" /></template>
