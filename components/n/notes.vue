<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/k/kgtfhz94h.css';
import '../../css/s/smdm4abnm.css';
import '../../css/u/u8vdedb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="kgtfhz94h"/><path class="smdm4abnm"/><path class="u8vdedb1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:notes" /></template>
