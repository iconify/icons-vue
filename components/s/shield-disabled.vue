<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnyag3brf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fnyag3brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shield-disabled" /></template>
