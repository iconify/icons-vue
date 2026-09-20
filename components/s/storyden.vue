<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xo8uvhurx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xo8uvhurx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:storyden" /></template>
