<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd66-6xai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dd66-6xai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:orc-head" /></template>
