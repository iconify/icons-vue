<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uymofrb9x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uymofrb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:planks" /></template>
