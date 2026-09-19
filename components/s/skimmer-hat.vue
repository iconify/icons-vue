<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxrpmbnwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hxrpmbnwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skimmer-hat" /></template>
