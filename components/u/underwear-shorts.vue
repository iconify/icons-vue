<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q75ec-jpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q75ec-jpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:underwear-shorts" /></template>
