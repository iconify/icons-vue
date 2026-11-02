<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyqm8vbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyqm8vbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-pin-pen-line" /></template>
