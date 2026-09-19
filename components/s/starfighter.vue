<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivsqt1wng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ivsqt1wng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:starfighter" /></template>
