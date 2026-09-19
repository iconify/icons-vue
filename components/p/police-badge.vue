<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq-h-bdhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mq-h-bdhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:police-badge" /></template>
