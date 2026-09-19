<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1-vgb93d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v1-vgb93d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:security-gate" /></template>
