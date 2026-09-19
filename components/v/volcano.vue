<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhoi73k-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mhoi73k-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:volcano" /></template>
