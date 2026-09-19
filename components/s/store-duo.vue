<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w2ulsp5ek.css';
import '../../css/v/vxm3ezfpe.css';
import '../../css/z/z6r-ddb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="w2ulsp5ek"/><path class="vxm3ezfpe"/><path class="z6r-ddb-m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:store-duo" /></template>
