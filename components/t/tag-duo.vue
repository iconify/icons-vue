<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nzbg1sbtp.css';
import '../../css/i/i1pf97t2i.css';
import '../../css/l/li3w9mbon.css';
import '../../css/w/w0p4f5bye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nzbg1sbtp"/><path class="i1pf97t2i"/><path class="li3w9mbon"/><path class="w0p4f5bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:tag-duo" /></template>
