<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sz0f1ls1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sz0f1ls1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:swamp-bat" /></template>
