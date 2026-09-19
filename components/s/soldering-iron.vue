<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v83gpgbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v83gpgbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:soldering-iron" /></template>
