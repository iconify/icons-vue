<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc18l2_6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mc18l2_6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:zigzag-hieroglyph" /></template>
