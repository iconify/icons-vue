<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-yle1b9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m-yle1b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:robot-helmet" /></template>
