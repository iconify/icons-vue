<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-7ny1epj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-7ny1epj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:select-circle-area-2" /></template>
