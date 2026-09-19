<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0u_zpb2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e0u_zpb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:turret" /></template>
