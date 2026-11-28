<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvgt0nbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kvgt0nbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:metronome" /></template>
