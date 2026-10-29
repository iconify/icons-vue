<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eziu-6b2h.css';
import '../../css/o/otle9ccjv.css';
import '../../css/i/i-v124nln.css';
import '../../css/z/z3fy_envj.css';
import '../../css/w/wp31-1bdq.css';
import '../../css/t/ty9mbdqxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eziu-6b2h wm-k"/><path class="otle9ccjv wm-a"/><path class="i-v124nln wm-shadow"/><path class="wm-k z3fy_envj"/><path class="wm-a wp31-1bdq"/><path class="ty9mbdqxq wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paste-engrave" /></template>
