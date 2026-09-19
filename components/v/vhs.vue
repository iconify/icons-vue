<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhiuo3b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dhiuo3b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:vhs" /></template>
