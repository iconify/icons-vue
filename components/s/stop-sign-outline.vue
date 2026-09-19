<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vn6abgphj.css';
import '../../css/t/t1skd0btf.css';
import '../../css/z/zymhpuznl.css';
import '../../css/i/il0c7wlxf.css';
import '../../css/d/dakxuccsp.css';
import '../../css/e/e34u2grox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vn6abgphj"/><path clip-rule="evenodd" class="t1skd0btf"/><path clip-rule="evenodd" class="zymhpuznl"/><path class="il0c7wlxf"/><path clip-rule="evenodd" class="dakxuccsp"/><path clip-rule="evenodd" class="e34u2grox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:stop-sign-outline" /></template>
