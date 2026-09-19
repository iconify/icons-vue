<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg01kfbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wg01kfbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pestle-mortar" /></template>
