<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uwrw1yo3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uwrw1yo3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sparky-bomb" /></template>
