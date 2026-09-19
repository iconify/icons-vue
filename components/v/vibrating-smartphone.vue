<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfoy-fbzs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yfoy-fbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vibrating-smartphone" /></template>
