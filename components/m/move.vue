<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r68-v8-yh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r68-v8-yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:move" /></template>
