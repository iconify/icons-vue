<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lt82r9lvc.css';
import '../../css/a/au0vr77bm.css';
import '../../css/m/map9qsb7c.css';
import '../../css/n/ntdufachd.css';
import '../../css/a/azzi-rk2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lt82r9lvc wm-shadow"/><path class="au0vr77bm wm-shadow"/><path class="map9qsb7c"/><path class="ntdufachd"/><path class="azzi-rk2o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:thumbs-up" /></template>
