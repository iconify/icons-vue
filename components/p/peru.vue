<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw_blcj2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mw_blcj2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:peru" /></template>
