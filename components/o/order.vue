<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/s/sb_9ycbok.css';
import '../../css/r/rl-0a4btd.css';
import '../../css/j/j6junebmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="sb_9ycbok"/><rect class="rl-0a4btd"/><path class="j6junebmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:order" /></template>
