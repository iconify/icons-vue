<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfmwm-blc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sfmwm-blc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:orange" /></template>
