<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_6-igbad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="n_6-igbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plant-watering" /></template>
