<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/obco2vbqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="obco2vbqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:sound-1" /></template>
