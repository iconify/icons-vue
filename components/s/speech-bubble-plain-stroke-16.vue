<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rcfb_cb7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="rcfb_cb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:speech-bubble-plain-stroke-16" /></template>
