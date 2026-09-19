<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/s/ske6nabae.css';
import '../../css/j/ju3i7pbvh.css';
import '../../css/s/sd78_u7bn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWVB6RddW"><g class="ufeehvblu"><path class="ske6nabae"/><path class="ju3i7pbvh"/><path class="sd78_u7bn"/></g></mask></defs><path mask="url(#SVGWVB6RddW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:table-report" /></template>
