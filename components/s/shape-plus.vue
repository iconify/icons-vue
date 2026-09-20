<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tiyci0bhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tiyci0bhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shape-plus" /></template>
