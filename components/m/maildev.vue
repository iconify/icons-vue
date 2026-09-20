<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz7wb2t7x.css';
import '../../css/v/vza9gr8cj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fz7wb2t7x"/><path class="vza9gr8cj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:maildev" /></template>
