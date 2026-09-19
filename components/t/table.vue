<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s221sp3wt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s221sp3wt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:table" /></template>
