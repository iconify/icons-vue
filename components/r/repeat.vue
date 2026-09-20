<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/g/g0z04lmhk.css';
import '../../css/n/np24xwb0n.css';
import '../../css/u/upk2z-g3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g0z04lmhk"/><path class="np24xwb0n"/><path class="upk2z-g3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:repeat" /></template>
