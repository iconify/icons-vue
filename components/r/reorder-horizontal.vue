<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdu0l2a4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gdu0l2a4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:reorder-horizontal" /></template>
