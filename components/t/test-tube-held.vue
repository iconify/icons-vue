<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i43839blh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i43839blh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:test-tube-held" /></template>
