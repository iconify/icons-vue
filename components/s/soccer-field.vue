<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6c6g4ssb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d6c6g4ssb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:soccer-field" /></template>
