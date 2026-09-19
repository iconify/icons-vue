<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnyajsi4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cnyajsi4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mushroom-gills" /></template>
