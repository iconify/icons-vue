<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyyqi6bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyyqi6bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:marquee-shutter" /></template>
