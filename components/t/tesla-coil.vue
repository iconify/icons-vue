<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-lvy5bqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u-lvy5bqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tesla-coil" /></template>
