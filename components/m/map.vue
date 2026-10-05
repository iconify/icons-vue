<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/m/m-gkls7fb.css';
import '../../css/x/x80s06bvh.css';
import '../../css/k/k1bgszu8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="m-gkls7fb"/><path class="x80s06bvh"/><path class="k1bgszu8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:map" /></template>
