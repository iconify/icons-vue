<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdtepbbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hdtepbbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skull-bolt" /></template>
