<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4fw_vbfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="k4fw_vbfo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:perspective-dice-six" /></template>
