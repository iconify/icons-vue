<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zhuru4w7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zhuru4w7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:medical-thermometer" /></template>
