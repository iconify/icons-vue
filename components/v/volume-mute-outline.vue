<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hyq94m6zf.css';
import '../../css/c/csc995bru.css';
import '../../css/u/ujj4w6bfn.css';
import '../../css/u/uqeizhbpa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="hyq94m6zf"/><path class="csc995bru"/><path clip-rule="evenodd" class="ujj4w6bfn"/><path class="uqeizhbpa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:volume-mute-outline" /></template>
