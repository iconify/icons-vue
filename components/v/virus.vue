<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xbes-8bdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xbes-8bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:virus" /></template>
