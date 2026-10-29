<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ifb93ynzy.css';
import '../../css/t/tq1j5cbbn.css';
import '../../css/b/bak33s4ai.css';
import '../../css/a/at880-k6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ifb93ynzy wm-k"/><path class="tq1j5cbbn wm-a"/><path class="bak33s4ai wm-k"/><path class="at880-k6w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:trending-down-sketch" /></template>
