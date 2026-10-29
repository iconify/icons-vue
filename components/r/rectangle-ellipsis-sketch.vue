<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ifoglu75k.css';
import '../../css/m/mq4e_tssq.css';
import '../../css/h/h9-2lpc6b.css';
import '../../css/u/uhkg0vb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ifoglu75k"/><path class="mq4e_tssq wm-a"/><path class="h9-2lpc6b wm-k"/><path class="uhkg0vb7d wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rectangle-ellipsis-sketch" /></template>
