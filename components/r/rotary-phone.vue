<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5_gxbcea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f5_gxbcea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rotary-phone" /></template>
