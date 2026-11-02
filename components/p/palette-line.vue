<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihb73o3yc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihb73o3yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:palette-line" /></template>
