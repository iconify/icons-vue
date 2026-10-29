<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/n/nxrh6pc1r.css';
import '../../css/j/j3czu2bly.css';
import '../../css/r/rxzr1qb1y.css';
import '../../css/f/fwu-keboc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="nxrh6pc1r"/><path class="j3czu2bly wm-k"/><path class="rxzr1qb1y wm-k"/><path class="fwu-keboc wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wine-sketch" /></template>
