<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/owmapqbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":368,"height":384};
const content = `<path class="owmapqbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-stream" /></template>
