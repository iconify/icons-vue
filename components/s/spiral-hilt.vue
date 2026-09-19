<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/py2_t-39j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="py2_t-39j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spiral-hilt" /></template>
