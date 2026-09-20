<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q12dtcbhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="q12dtcbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:racetrack-oval-with-dashes" /></template>
