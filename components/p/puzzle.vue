<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hgqtju7yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hgqtju7yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:puzzle" /></template>
