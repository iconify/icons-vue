<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcsogpb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dcsogpb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:sword-in-stone" /></template>
