<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fob3lobvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fob3lobvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:roman-shield" /></template>
