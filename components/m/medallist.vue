<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/isz-uwbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="isz-uwbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:medallist" /></template>
