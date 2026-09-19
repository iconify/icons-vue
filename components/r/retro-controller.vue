<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s35u49yim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s35u49yim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:retro-controller" /></template>
