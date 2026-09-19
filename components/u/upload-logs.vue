<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/v/vbd70wppp.css';
import '../../css/s/s41omdbbh.css';
import '../../css/l/lb3mijz1r.css';
import '../../css/l/lvmdmwb6j.css';
import '../../css/e/eh2fp3h8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="vbd70wppp"/><path class="s41omdbbh"/><path class="lb3mijz1r"/><path class="lvmdmwb6j"/><path class="eh2fp3h8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:upload-logs" /></template>
