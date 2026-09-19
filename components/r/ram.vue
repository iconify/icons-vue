<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hj9vgb4-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hj9vgb4-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:ram" /></template>
