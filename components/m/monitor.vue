<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/n/ntzi1w4nm.css';
import '../../css/w/w_k0w4xei.css';
import '../../css/r/r-c_vcb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="ntzi1w4nm"/><path class="w_k0w4xei"/><path class="r-c_vcb4h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:monitor" /></template>
