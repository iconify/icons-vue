<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7ffexbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z7ffexbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:wire-coil" /></template>
