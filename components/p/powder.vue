<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ocb9_nbex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ocb9_nbex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:powder" /></template>
