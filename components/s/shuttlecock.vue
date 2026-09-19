<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvzl_-vef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uvzl_-vef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shuttlecock" /></template>
