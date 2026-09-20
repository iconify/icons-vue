<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/ztp-9fb2o.css';
import '../../css/u/ureme7j-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztp-9fb2o"/><path class="ureme7j-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:time-hourglass-triangle" /></template>
