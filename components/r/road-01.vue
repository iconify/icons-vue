<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddvgu8bvv.css';
import '../../css/o/ob40y1u8s.css';
import '../../css/o/ov4muo9iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="ob40y1u8s"/><path class="ov4muo9iz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:road-01" /></template>
