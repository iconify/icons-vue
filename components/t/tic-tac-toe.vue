<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hww2_jbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hww2_jbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tic-tac-toe" /></template>
