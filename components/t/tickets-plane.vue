<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lpusqwbwb.css';
import '../../css/n/nagqqvblc.css';
import '../../css/n/nj4w60bmc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lpusqwbwb"/><path class="nagqqvblc"/><path class="nj4w60bmc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tickets-plane" /></template>
