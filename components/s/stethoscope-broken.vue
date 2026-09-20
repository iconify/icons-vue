<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vlicqjwnt.css';
import '../../css/a/a8o0ttbfc.css';
import '../../css/m/me86ccc_a.css';
import '../../css/x/x_jwp_bge.css';
import '../../css/y/yy3grib4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vlicqjwnt"/><path class="a8o0ttbfc"/><circle class="me86ccc_a"/><path class="x_jwp_bge"/><path class="yy3grib4x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stethoscope-broken" /></template>
