<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn8nh4bdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xn8nh4bdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-13-death" /></template>
