<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l992fn8dq.css';
import '../../css/v/vcqc0q5py.css';
import '../../css/s/s5vsshbss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="l992fn8dq"/><path class="vcqc0q5py"/><path class="s5vsshbss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pin-off" /></template>
