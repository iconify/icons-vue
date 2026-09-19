<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm9sx5blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wm9sx5blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fad:waveform" /></template>
