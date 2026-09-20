<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu__29aqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zu__29aqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:vimeo" /></template>
