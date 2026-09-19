<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx2j-7z0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sx2j-7z0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tropical-fish" /></template>
