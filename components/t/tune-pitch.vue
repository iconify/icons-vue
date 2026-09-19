<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tava8bboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tava8bboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tune-pitch" /></template>
