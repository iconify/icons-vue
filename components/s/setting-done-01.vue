<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hav_9b5ms.css';
import '../../css/j/jmluh1b1c.css';
import '../../css/l/ltnpeeb1q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hav_9b5ms"/><path class="jmluh1b1c"/><path class="ltnpeeb1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:setting-done-01" /></template>
