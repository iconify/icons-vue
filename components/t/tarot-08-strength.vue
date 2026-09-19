<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hq62yebju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="hq62yebju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:tarot-08-strength" /></template>
