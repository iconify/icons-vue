<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klvi3bcrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="klvi3bcrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spikes-init" /></template>
