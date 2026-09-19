<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iql1lvbzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iql1lvbzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:pathfinder-unite" /></template>
