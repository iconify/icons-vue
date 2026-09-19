<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn7rc-bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cn7rc-bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:shouting" /></template>
