<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0u_vcc-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r0u_vcc-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:solar-system" /></template>
