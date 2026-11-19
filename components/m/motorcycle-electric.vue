<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/t/twnizym5a.css';
import '../../css/m/myf-6ebsp.css';
import '../../css/e/evobmbbsy.css';
import '../../css/i/i7gj7vbxl.css';
import '../../css/g/gd_e071ev.css';
import '../../css/q/qn9w10f3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="twnizym5a"/><circle class="myf-6ebsp"/><rect class="evobmbbsy"/><path class="i7gj7vbxl"/><path class="gd_e071ev"/><path class="qn9w10f3c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:motorcycle-electric" /></template>
