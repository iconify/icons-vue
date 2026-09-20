<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qidbiubrb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qidbiubrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:stopwatch-three-quarter-remix" /></template>
