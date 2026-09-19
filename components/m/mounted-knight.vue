<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mm_hg97ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mm_hg97ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:mounted-knight" /></template>
