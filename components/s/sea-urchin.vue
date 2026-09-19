<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nh4s1z2xe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nh4s1z2xe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sea-urchin" /></template>
