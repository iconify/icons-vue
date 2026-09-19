<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dcdirwbkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dcdirwbkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:robber" /></template>
