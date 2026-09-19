<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lzz7smhdu.css';
import '../../css/v/v_ctii0wf.css';
import '../../css/l/lgngwe9qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lzz7smhdu"/><path class="v_ctii0wf"/><path class="lgngwe9qv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:satellite-duo" /></template>
