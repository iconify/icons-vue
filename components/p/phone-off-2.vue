<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpmv5nbra.css';
import '../../css/h/h5bun4ehf.css';
import '../../css/h/hm6t7gb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qpmv5nbra"/><path class="h5bun4ehf"/><path class="hm6t7gb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:phone-off-2" /></template>
