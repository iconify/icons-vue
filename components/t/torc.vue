<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iy5cukbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iy5cukbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:torc" /></template>
