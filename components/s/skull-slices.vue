<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ee_pagbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ee_pagbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skull-slices" /></template>
