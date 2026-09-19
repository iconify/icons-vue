<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myrlwzbds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="myrlwzbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skeleton-key" /></template>
