<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/b51-lhp3z.css';
import '../../css/s/se2qxethe.css';
import '../../css/g/gp4pu0sxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><rect class="b51-lhp3z"/><path class="se2qxethe"/><path class="gp4pu0sxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:nine-key" /></template>
