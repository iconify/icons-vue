<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hb4nc0b1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hb4nc0b1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:video-camera" /></template>
