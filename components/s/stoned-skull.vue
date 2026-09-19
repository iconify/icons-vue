<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqrvfl7vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wqrvfl7vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:stoned-skull" /></template>
