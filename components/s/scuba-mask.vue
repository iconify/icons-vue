<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5m7rab3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r5m7rab3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:scuba-mask" /></template>
