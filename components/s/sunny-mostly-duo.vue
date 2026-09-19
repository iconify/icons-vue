<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g_0ex7y7n.css';
import '../../css/z/zn5wvtzfp.css';
import '../../css/z/zx8orabuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="g_0ex7y7n"/><path class="zn5wvtzfp"/><path class="zx8orabuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sunny-mostly-duo" /></template>
