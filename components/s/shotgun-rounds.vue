<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nan84cbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nan84cbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shotgun-rounds" /></template>
