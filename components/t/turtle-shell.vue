<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jruk4-ytp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jruk4-ytp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:turtle-shell" /></template>
