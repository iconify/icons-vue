<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hvak45gtf.css';
import '../../css/m/m3w7a8b7o.css';
import '../../css/r/rsrhfac5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hvak45gtf"/><path class="m3w7a8b7o"/><path class="rsrhfac5n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:printer-slash" /></template>
