<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp97lfoxd.css';
import '../../css/k/k3ypocbdl.css';
import '../../css/t/tspdbdasy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="rp97lfoxd"><path clip-rule="evenodd" class="k3ypocbdl"/><path class="tspdbdasy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:pause" /></template>
