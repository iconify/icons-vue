<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymfss1b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ymfss1b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:two-shadows" /></template>
