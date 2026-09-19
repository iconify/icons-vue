<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mom0oactl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mom0oactl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rainbow-star" /></template>
