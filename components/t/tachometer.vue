<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g-briy-mv.css';
import '../../css/q/qhogk5bhw.css';
import '../../css/g/gyvacpo7m.css';
import '../../css/f/f5oksfbop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="g-briy-mv"/><path class="qhogk5bhw"/><path class="gyvacpo7m"/><path class="f5oksfbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:tachometer" /></template>
