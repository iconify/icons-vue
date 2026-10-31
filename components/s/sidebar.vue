<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/p/poaw18_iz.css';
import '../../css/m/ml2lq6y_v.css';
import '../../css/a/ao21d5blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="poaw18_iz"/><path class="ml2lq6y_v wm-shine"/><path class="ao21d5blb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:sidebar" /></template>
