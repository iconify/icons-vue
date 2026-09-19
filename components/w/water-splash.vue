<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwrbt_kpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nwrbt_kpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:water-splash" /></template>
