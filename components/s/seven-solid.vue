<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oem3dgbor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oem3dgbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:seven-solid" /></template>
