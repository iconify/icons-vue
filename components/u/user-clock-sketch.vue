<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/krwaskb4k.css';
import '../../css/j/j8pt22lgn.css';
import '../../css/p/p315kqhvz.css';
import '../../css/b/b25ralmkw.css';
import '../../css/f/fpe-trb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="krwaskb4k"/><path class="j8pt22lgn wm-k"/><path class="p315kqhvz wm-s"/><path class="b25ralmkw wm-k"/><path class="fpe-trb0t wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-clock-sketch" /></template>
