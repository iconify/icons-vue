<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhy3c0lxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhy3c0lxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scarab-beetle" /></template>
