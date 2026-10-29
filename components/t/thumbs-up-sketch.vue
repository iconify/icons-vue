<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vcj0rxbfv.css';
import '../../css/u/uam27y2rr.css';
import '../../css/r/r8t9kbczu.css';
import '../../css/r/rj-hvabwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vcj0rxbfv"/><path class="uam27y2rr wm-k"/><path class="r8t9kbczu wm-k"/><path class="rj-hvabwd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thumbs-up-sketch" /></template>
