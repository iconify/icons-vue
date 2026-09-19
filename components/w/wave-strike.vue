<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwu2lbb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wwu2lbb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wave-strike" /></template>
