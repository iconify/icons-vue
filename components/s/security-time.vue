<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/q3-6cmb1n.css';
import '../../css/r/r_7aq8m-i.css';
import '../../css/r/r0wv4tb5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3-6cmb1n"/><path class="r_7aq8m-i"/><path class="r0wv4tb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:security-time" /></template>
