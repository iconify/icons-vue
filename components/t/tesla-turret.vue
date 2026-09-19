<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azk1c0b3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="azk1c0b3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tesla-turret" /></template>
