<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mti108opm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mti108opm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:volume-level-high-remix" /></template>
