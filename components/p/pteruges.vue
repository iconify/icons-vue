<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnl6s70sd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dnl6s70sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:pteruges" /></template>
