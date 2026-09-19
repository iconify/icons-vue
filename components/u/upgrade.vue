<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw-otcbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yw-otcbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:upgrade" /></template>
