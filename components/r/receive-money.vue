<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nk83ul6px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nk83ul6px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:receive-money" /></template>
