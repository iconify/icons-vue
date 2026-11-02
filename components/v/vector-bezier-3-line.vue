<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlntbmarp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlntbmarp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vector-bezier-3-line" /></template>
