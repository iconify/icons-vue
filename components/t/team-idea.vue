<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqjy40bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zqjy40bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:team-idea" /></template>
