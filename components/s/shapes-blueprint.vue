<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/j_b2pwsiw.css';
import '../../css/h/hlv6ql6jp.css';
import '../../css/p/pbtr10c0j.css';
import '../../css/p/puwr3dbsv.css';
import '../../css/v/vqvr78bzf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="j_b2pwsiw wm-deco"/><path class="hlv6ql6jp wm-deco"/><path class="pbtr10c0j wm-deco"/><path class="puwr3dbsv wm-k"/><path class="vqvr78bzf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shapes-blueprint" /></template>
