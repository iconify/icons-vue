<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yuezgabks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yuezgabks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:staryu" /></template>
