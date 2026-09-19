<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bweh7qb2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bweh7qb2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiked-wall" /></template>
