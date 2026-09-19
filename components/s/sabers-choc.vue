<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhwhxl1gh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hhwhxl1gh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sabers-choc" /></template>
