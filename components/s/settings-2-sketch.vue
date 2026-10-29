<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g-xwnsrlt.css';
import '../../css/r/rqx6b27ni.css';
import '../../css/m/msccn7b6y.css';
import '../../css/k/kswlmacai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g-xwnsrlt wm-a"/><path class="rqx6b27ni wm-k"/><path class="msccn7b6y wm-a"/><path class="kswlmacai wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:settings-2-sketch" /></template>
