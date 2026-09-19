<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-mxhdbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y-mxhdbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mars-curiosity" /></template>
