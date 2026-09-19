<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itl2fpwcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="itl2fpwcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:small-fishing-sailboat" /></template>
