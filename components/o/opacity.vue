<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwk82bc5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwk82bc5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:opacity" /></template>
