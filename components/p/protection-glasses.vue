<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywnk-4bol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywnk-4bol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:protection-glasses" /></template>
