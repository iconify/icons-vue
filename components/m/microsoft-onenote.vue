<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpvtopbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpvtopbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:microsoft-onenote" /></template>
