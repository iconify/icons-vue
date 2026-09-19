<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mzdz8f2mo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mzdz8f2mo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stabbed-note" /></template>
