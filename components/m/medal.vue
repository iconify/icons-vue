<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/a99dawbxs.css';
import '../../css/o/ou4llgytr.css';
import '../../css/r/rui3uwbpt.css';
import '../../css/x/xq8ohifvd.css';
import '../../css/r/rhraiil6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="a99dawbxs wm-shadow"/><path class="ou4llgytr wm-shadow"/><path class="rui3uwbpt"/><path class="xq8ohifvd"/><path class="rhraiil6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:medal" /></template>
