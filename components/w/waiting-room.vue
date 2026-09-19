<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz06e3bkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz06e3bkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:waiting-room" /></template>
