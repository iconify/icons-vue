<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/h/hmqkr95yr.css';
import '../../css/c/cxgt2g6hf.css';
import '../../css/t/tiz7iu3-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmqkr95yr"/><path class="cxgt2g6hf"/><path class="tiz7iu3-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tree-07" /></template>
