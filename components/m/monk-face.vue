<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu4dusbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fu4dusbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:monk-face" /></template>
