<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4p4-82my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q4p4-82my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:slap" /></template>
