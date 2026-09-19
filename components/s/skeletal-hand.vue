<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr8q3pbmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kr8q3pbmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:skeletal-hand" /></template>
