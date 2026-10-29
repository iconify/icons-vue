<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/i_1xs8ezl.css';
import '../../css/j/jcugpbcrt.css';
import '../../css/e/erfo6-egg.css';
import '../../css/p/psaadlbfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="i_1xs8ezl"/><path class="jcugpbcrt wm-k"/><path class="erfo6-egg wm-k"/><path class="psaadlbfa wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:signpost-sketch" /></template>
