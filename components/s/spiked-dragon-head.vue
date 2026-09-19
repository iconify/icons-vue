<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmk8_o-us.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rmk8_o-us"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiked-dragon-head" /></template>
