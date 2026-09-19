<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zsbt4b50t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zsbt4b50t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:time-dynamite" /></template>
