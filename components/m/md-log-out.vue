<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi-wnz67i.css';
import '../../css/e/eopo7lbmx.css';
import '../../css/p/p4xyc1bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vi-wnz67i"/><path class="eopo7lbmx"/><path class="p4xyc1bjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-log-out" /></template>
