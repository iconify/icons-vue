<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/teo0ohb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="teo0ohb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:riposte" /></template>
