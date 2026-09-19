<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj0p3-b1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uj0p3-b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tadpole" /></template>
