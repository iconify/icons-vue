<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ivpju1dvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ivpju1dvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shaking-hands" /></template>
