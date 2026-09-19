<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f11ni23_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f11ni23_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:smoking-volcano" /></template>
