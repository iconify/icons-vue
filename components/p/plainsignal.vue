<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sl_3r4agh.css';
import '../../css/r/r2juzqsgu.css';
import '../../css/h/ha3xd_bqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="bi12bsetm"><rect class="sl_3r4agh"/><circle class="r2juzqsgu"/><path class="ha3xd_bqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:plainsignal" /></template>
