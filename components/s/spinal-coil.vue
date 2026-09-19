<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifk-m6b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ifk-m6b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spinal-coil" /></template>
