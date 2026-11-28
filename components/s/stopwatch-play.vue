<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nphau5bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nphau5bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:stopwatch-play" /></template>
