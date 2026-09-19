<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/busrn3bwc.css';
import '../../css/w/worcco0zv.css';
import '../../css/e/eswimnb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="busrn3bwc"/><path class="worcco0zv"/><path class="eswimnb4q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:wallet-not-found-01" /></template>
