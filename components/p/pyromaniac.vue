<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nit60o93h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nit60o93h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pyromaniac" /></template>
