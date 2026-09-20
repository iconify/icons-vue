<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6x7wfcnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6x7wfcnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:wireless-charging-line" /></template>
