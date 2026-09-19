<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjde_6bez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yjde_6bez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trail" /></template>
