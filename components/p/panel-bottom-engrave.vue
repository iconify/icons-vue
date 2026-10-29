<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cjtghllwe.css';
import '../../css/g/gl--lubve.css';
import '../../css/e/e2_mtpbne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cjtghllwe"/><path class="gl--lubve wm-shadow"/><path class="e2_mtpbne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-bottom-engrave" /></template>
