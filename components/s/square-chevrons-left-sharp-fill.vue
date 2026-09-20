<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wf1crc8bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wf1crc8bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-chevrons-left-sharp-fill" /></template>
