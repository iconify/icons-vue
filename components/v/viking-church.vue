<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xso4m5s-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xso4m5s-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:viking-church" /></template>
