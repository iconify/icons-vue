<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8_q7kbcv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h8_q7kbcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:male" /></template>
