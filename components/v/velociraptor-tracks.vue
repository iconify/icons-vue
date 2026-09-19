<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xin-pnb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xin-pnb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:velociraptor-tracks" /></template>
