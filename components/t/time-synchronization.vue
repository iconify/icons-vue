<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5mkn8bzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w5mkn8bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:time-synchronization" /></template>
