<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmr-5ubui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmr-5ubui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-minus" /></template>
