<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6ypdacha.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z6ypdacha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:oak-leaf" /></template>
