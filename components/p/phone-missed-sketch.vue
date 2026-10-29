<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/ae206tbtt.css';
import '../../css/c/cg-lnu7pb.css';
import '../../css/z/zrzjcwbuq.css';
import '../../css/q/q4pv1lb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ae206tbtt"/><path class="cg-lnu7pb wm-s"/><path class="wm-k zrzjcwbuq"/><path class="q4pv1lb0v wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone-missed-sketch" /></template>
