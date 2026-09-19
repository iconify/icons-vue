<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz0lrob5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fz0lrob5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:totem-mask" /></template>
