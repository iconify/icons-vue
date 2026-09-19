<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/v/vjqi9gboy.css';
import '../../css/w/wrqafjrbc.css';
import '../../css/b/bun8441ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="vjqi9gboy"/><path class="wrqafjrbc"/><path class="bun8441ri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:vacation" /></template>
