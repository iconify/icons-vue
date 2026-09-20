<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/n/n57ixwbvq.css';
import '../../css/s/s1gyzwksf.css';
import '../../css/y/ycrm45b1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n57ixwbvq"/><path class="s1gyzwksf"/><path class="ycrm45b1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:spider" /></template>
