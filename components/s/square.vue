<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj3wflbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wj3wflbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:square" /></template>
