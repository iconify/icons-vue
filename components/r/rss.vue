<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/d/d7m39n8ut.css';
import '../../css/u/ur70ribyv.css';
import '../../css/q/q1x80pbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="d7m39n8ut"/><path class="ur70ribyv"/><path class="q1x80pbnz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:rss" /></template>
