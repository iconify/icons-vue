<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7x4lpb9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o7x4lpb9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:phrygian-cap" /></template>
