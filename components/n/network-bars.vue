<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hcm8mkbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hcm8mkbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:network-bars" /></template>
