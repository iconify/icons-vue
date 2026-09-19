<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie2v73wnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ie2v73wnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:warhammer" /></template>
