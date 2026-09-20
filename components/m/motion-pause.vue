<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k4fq1ibme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4fq1ibme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:motion-pause" /></template>
