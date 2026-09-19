<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pu6y1bchq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pu6y1bchq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:parasaurolophus" /></template>
