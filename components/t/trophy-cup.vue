<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4g349b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o4g349b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trophy-cup" /></template>
