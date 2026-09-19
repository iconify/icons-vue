<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eb-8p7lsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eb-8p7lsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:metronome" /></template>
