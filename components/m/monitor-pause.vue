<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/o0fo8ebji.css';
import '../../css/r/r8-cjywgb.css';
import '../../css/h/h7focp4gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o0fo8ebji"/><rect class="r8-cjywgb"/><path class="h7focp4gr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:monitor-pause" /></template>
