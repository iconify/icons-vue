<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d100xbbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d100xbbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mine-truck" /></template>
