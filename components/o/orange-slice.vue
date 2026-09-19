<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdt1xv_kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qdt1xv_kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:orange-slice" /></template>
