<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2z5tnbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r2z5tnbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:vigilant-monitor" /></template>
