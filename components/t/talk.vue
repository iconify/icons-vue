<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs9g5f4wp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hs9g5f4wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:talk" /></template>
