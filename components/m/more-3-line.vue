<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wa9uavbmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wa9uavbmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:more-3-line" /></template>
