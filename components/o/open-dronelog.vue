<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ym6wy1brw.css';
import '../../css/g/gtz84wbsv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ym6wy1brw"/><path class="gtz84wbsv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:open-dronelog" /></template>
