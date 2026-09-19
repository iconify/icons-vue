<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/l/lvzgdqdyq.css';
import '../../css/y/y36yww21t.css';
import '../../css/j/jcocdpb8j.css';
import '../../css/i/iwe9abbhf.css';
import '../../css/s/sr6x3ialb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path clip-rule="evenodd" class="lvzgdqdyq"/><path class="y36yww21t"/><path class="jcocdpb8j"/><path class="iwe9abbhf"/><path class="sr6x3ialb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:sd-card" /></template>
