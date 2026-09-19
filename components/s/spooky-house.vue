<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fhp6d1bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fhp6d1bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:spooky-house" /></template>
