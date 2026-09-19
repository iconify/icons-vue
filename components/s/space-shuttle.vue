<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9z9uobwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d9z9uobwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:space-shuttle" /></template>
