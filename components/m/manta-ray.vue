<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m3f125bxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m3f125bxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:manta-ray" /></template>
