<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkor7rb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pkor7rb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:round-star" /></template>
