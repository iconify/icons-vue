<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mspky1buw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mspky1buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sausage" /></template>
