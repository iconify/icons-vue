<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmdj_8bqw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cmdj_8bqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tow-truck" /></template>
