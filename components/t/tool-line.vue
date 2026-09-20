<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxmz_6bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nxmz_6bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tool-line" /></template>
