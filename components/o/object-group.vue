<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqyr_1b6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqyr_1b6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:object-group" /></template>
