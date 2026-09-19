<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbhx81bpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="kbhx81bpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:pano" /></template>
