<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t45nv2adc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t45nv2adc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:now" /></template>
