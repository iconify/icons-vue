<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iet_bbczh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iet_bbczh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:plane-pilot" /></template>
