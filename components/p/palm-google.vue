<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve369n4ju.css';
import '../../css/d/d2wy5eb5e.css';
import '../../css/h/hj0knpbrn.css';
import '../../css/d/dxws9lb6d.css';
import '../../css/g/g565v1buv.css';
import '../../css/o/orpqezbqt.css';
import '../../css/v/vxzxcv0wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ve369n4ju"/><path class="d2wy5eb5e"/><path class="hj0knpbrn"/><path class="dxws9lb6d"/><path class="g565v1buv"/><path class="orpqezbqt"/><path class="vxzxcv0wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:palm-google" /></template>
