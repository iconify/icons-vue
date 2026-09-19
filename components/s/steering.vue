<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/u/uwy-gqb8h.css';
import '../../css/j/jw704zd0t.css';
import '../../css/j/j8iq9-ffs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="uwy-gqb8h"/><path class="jw704zd0t"/><path class="j8iq9-ffs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:steering" /></template>
