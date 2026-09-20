<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s26owg8ed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s26owg8ed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stopwatch-play" /></template>
