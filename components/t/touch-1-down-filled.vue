<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp8-mcbwg.css';
import '../../css/n/nd-6u87gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rp8-mcbwg"/><path class="nd-6u87gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:touch-1-down-filled" /></template>
