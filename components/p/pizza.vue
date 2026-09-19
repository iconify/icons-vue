<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ice-5lmvf.css';
import '../../css/o/oafign_da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ice-5lmvf"/><path class="oafign_da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:pizza" /></template>
