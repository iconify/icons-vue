<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny-33twob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ny-33twob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tennis-racket" /></template>
