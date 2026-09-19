<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/id1l07j3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="id1l07j3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:military-ambulance" /></template>
