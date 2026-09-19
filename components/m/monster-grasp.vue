<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njcyhccme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="njcyhccme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:monster-grasp" /></template>
