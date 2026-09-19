<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdodnt-vb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pdodnt-vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vortex" /></template>
