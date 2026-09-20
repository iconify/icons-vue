<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqu5qwbpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqu5qwbpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-beam-note" /></template>
