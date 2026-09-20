<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/pvl6bvbyg.css';
import '../../css/u/uu4o2hbdh.css';
import '../../css/a/aty_qzhdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pvl6bvbyg"/><path class="uu4o2hbdh"/><path class="aty_qzhdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:wallet5" /></template>
