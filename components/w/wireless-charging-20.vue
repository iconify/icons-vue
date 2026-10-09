<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e5m23wblo.css';
import '../../css/w/wg0eo9hxf.css';
import '../../css/z/zy2qlf16k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e5m23wblo"/><path class="wg0eo9hxf"/><path class="zy2qlf16k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wireless-charging-20" /></template>
