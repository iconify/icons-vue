<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmdgjrwsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jmdgjrwsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-outlook-2000-dark" /></template>
