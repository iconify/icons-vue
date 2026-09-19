<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orf3lfbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="orf3lfbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:melting-ice-cube" /></template>
