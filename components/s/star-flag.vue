<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx1qjcbmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xx1qjcbmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:star-flag" /></template>
