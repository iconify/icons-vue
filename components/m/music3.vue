<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jmv2f3b2c.css';
import '../../css/r/rp05lmnnc.css';
import '../../css/v/v_mzr6b6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jmv2f3b2c"/><path class="rp05lmnnc"/><path class="v_mzr6b6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:music3" /></template>
