<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/u/ucionx-lv.css';
import '../../css/y/ybxw_bc8q.css';
import '../../css/i/id7402b9s.css';
import '../../css/a/ayju-qj-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ufeehvblu"><path class="ucionx-lv"/><ellipse class="ybxw_bc8q"/><path class="id7402b9s"/><path class="ayju-qj-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:music-list" /></template>
