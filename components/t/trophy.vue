<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qel0rlrpg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qel0rlrpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:trophy" /></template>
