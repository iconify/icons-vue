<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/n/n7hf31buy.css';
import '../../css/d/da0v6yu7c.css';
import '../../css/g/gmjd0tb9a.css';
import '../../css/d/ddal_tbtn.css';
import '../../css/j/jxlyp1b3g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="n7hf31buy"/><path class="da0v6yu7c"/><path class="gmjd0tb9a wm-shine"/><path class="ddal_tbtn wm-k"/><path class="jxlyp1b3g wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:piano" /></template>
