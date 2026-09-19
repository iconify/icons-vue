<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r0_0hibhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r0_0hibhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:police-target" /></template>
