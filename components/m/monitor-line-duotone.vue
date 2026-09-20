<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wx2_qhbxs.css';
import '../../css/n/ny2yxtbss.css';
import '../../css/t/ta0zdfd_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wx2_qhbxs"/><path class="ny2yxtbss"/><path class="ta0zdfd_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:monitor-line-duotone" /></template>
