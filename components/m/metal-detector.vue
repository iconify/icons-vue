<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgw4z_mvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mgw4z_mvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:metal-detector" /></template>
