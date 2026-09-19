<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekf16vbut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ekf16vbut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plain-square" /></template>
