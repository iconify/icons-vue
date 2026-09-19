<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldtsa3zvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ldtsa3zvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stable" /></template>
