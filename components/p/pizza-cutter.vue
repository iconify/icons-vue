<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv8ph2xqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nv8ph2xqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pizza-cutter" /></template>
