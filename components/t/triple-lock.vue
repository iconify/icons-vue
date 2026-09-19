<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw6h11bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cw6h11bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:triple-lock" /></template>
