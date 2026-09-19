<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqz3f3blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oqz3f3blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:over-infinity" /></template>
