<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iypo-rqra.css';
import '../../css/y/y2-zu1b4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iypo-rqra"/><path class="y2-zu1b4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scrubber-20" /></template>
