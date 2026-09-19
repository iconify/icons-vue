<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhj2skbky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mhj2skbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:semi-closed-eye" /></template>
