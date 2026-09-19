<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m0xrrzbhk.css';
import '../../css/b/bzwyxw3nr.css';
import '../../css/q/qosxyynna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="m0xrrzbhk"/><path class="bzwyxw3nr"/><path class="qosxyynna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:seo-folder" /></template>
