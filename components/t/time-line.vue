<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8wto_7ev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8wto_7ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:time-line" /></template>
