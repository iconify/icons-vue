<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyu31ob2a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="eyu31ob2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:turd" /></template>
