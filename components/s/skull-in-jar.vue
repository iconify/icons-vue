<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmo3-snvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rmo3-snvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skull-in-jar" /></template>
