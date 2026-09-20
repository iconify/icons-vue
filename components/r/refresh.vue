<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/w/wr8trj8pf.css';
import '../../css/n/nvor0_msi.css';
import '../../css/o/oz_5o-o8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wr8trj8pf"/><path class="nvor0_msi"/><path class="oz_5o-o8f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:refresh" /></template>
