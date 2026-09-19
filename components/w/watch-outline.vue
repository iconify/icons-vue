<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q2p1-kb8b.css';
import '../../css/h/hbn7adl-e.css';
import '../../css/i/ibft8obap.css';
import '../../css/h/hpuq-ubde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q2p1-kb8b"/><path class="hbn7adl-e"/><path class="ibft8obap"/><path class="hpuq-ubde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:watch-outline" /></template>
