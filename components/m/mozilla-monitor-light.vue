<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pi7f4wb8o.css';
import '../../css/g/gbm6d6bzt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pi7f4wb8o"/><path class="gbm6d6bzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:mozilla-monitor-light" /></template>
