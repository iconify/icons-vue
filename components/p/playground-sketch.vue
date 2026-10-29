<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eh56edcyw.css';
import '../../css/t/t8a7fpred.css';
import '../../css/a/awkx36b2i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eh56edcyw wm-k"/><path class="t8a7fpred wm-k"/><path class="awkx36b2i wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:playground-sketch" /></template>
