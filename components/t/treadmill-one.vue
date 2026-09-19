<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti4q6eknm.css';
import '../../css/b/bkycwstta.css';
import '../../css/j/jknat6yla.css';
import '../../css/l/lba8bpl1h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ti4q6eknm"><path class="bkycwstta"/><path class="jknat6yla"/><path class="lba8bpl1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:treadmill-one" /></template>
