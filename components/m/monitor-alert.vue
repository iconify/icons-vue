<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s72dk49og.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s72dk49og"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:monitor-alert" /></template>
