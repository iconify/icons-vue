<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpptl4bab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wpptl4bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:triple-needle" /></template>
