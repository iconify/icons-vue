<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch0uwabrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ch0uwabrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:oat" /></template>
