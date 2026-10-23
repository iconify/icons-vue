<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/d/d8vkrvboc.css';
import '../../css/g/g62c_b0ym.css';
import '../../css/c/coa5w3v0h.css';
import '../../css/u/uh0qp9b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="d8vkrvboc"/><path class="g62c_b0ym"/><path class="coa5w3v0h"/><path class="uh0qp9b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:qr-code" /></template>
