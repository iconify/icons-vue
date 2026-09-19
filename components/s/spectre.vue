<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rucms2b7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rucms2b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spectre" /></template>
