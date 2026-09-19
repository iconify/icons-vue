<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jveo_3b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jveo_3b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spider-web" /></template>
