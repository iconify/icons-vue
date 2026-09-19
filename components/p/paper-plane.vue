<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbzdh2bun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tbzdh2bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paper-plane" /></template>
