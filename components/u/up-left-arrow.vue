<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7amu7_fh.css';
import '../../css/f/ftfoyqbcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="h7amu7_fh"/><path class="ftfoyqbcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:up-left-arrow" /></template>
