<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfgh54_oh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pfgh54_oh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skills" /></template>
