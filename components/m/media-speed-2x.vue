<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojm9wsbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":24};
const content = `<path class="ojm9wsbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:media-speed-2x" /></template>
