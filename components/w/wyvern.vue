<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-cp04bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-cp04bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wyvern" /></template>
