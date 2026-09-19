<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh1-gqbnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sh1-gqbnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mooring-bollard" /></template>
