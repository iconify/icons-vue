<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ia_ti1b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ia_ti1b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spikes-half" /></template>
