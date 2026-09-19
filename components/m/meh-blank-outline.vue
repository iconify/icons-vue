<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kg11nj89m.css';
import '../../css/q/qhilh8bcr.css';
import '../../css/k/kiqr8zzyi.css';
import '../../css/n/nzmh0imzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="kg11nj89m"/><path clip-rule="evenodd" class="qhilh8bcr"/><path class="kiqr8zzyi"/><path clip-rule="evenodd" class="nzmh0imzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:meh-blank-outline" /></template>
