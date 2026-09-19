<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smig3ccbw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smig3ccbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:motion-sensor-luminance" /></template>
