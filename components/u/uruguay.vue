<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkxt-8bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rkxt-8bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:uruguay" /></template>
