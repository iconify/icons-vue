<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pa7yzpbyc.css';
import '../../css/b/bn-2pebwd.css';
import '../../css/s/srwmimt6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pa7yzpbyc"/><path class="bn-2pebwd"/><path class="srwmimt6b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:sticky-notes" /></template>
