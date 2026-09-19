<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi9v3xbuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oi9v3xbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:monument-valley" /></template>
