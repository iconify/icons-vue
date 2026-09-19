<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u59ysr_vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u59ysr_vi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:rolled-cloth" /></template>
