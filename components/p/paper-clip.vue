<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipjl01bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ipjl01bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:paper-clip" /></template>
