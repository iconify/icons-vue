<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk1fx-k4e.css';
import '../../css/n/nfdtw2x4x.css';
import '../../css/b/bcm2eibfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="tk1fx-k4e"><path class="nfdtw2x4x"/><path class="bcm2eibfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:two-semicircles" /></template>
