<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfgvi2btw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mfgvi2btw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:periscope" /></template>
