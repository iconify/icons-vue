<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/h/hjxju6mct.css';
import '../../css/h/hr_fn_bfr.css';
import '../../css/p/p0gu5dbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="hjxju6mct"/><path class="hr_fn_bfr"/><path class="p0gu5dbyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:sky-lantern" /></template>
