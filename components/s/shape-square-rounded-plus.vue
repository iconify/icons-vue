<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/last7kb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="last7kb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:shape-square-rounded-plus" /></template>
