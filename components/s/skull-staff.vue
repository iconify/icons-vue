<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lo2ghhbip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="lo2ghhbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skull-staff" /></template>
