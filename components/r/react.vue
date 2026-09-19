<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jq1l036pk.css';
import '../../css/z/zpl7y2bfy.css';
import '../../css/c/cykosrb4t.css';
import '../../css/w/wy0fhnajo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jq1l036pk"/><path class="zpl7y2bfy"/><path class="cykosrb4t"/><path class="wy0fhnajo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:react" /></template>
