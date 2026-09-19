<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yazs0eb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yazs0eb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:round-knob" /></template>
