<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3lph30dl.css';
import '../../css/u/uwh4irbxb.css';
import '../../css/v/v3kw5acxg.css';
import '../../css/j/j-npdpb0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="uwh4irbxb"/><path class="v3kw5acxg"/><line x1="11" x2="11" y1="8" y2="11" class="j-npdpb0r"/><line x1="35" x2="35" y1="8" y2="11" class="j-npdpb0r"/><line x1="23" x2="23" y1="5" y2="11" class="j-npdpb0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:tea" /></template>
