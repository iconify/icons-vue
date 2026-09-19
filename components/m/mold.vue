<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f4twacccu.css';
import '../../css/v/vm32y5bcp.css';
import '../../css/p/p08x5tbis.css';
import '../../css/r/rbd59kb7g.css';
import '../../css/w/wgj9pd01c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f4twacccu"/><path class="vm32y5bcp"/><path class="p08x5tbis"/><rect class="rbd59kb7g"/><rect class="wgj9pd01c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:mold" /></template>
