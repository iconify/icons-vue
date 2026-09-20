<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/b/bnkim_jww.css';
import '../../css/w/wjg491cmr.css';
import '../../css/p/pl4wavb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bnkim_jww"/><path class="wjg491cmr"/><path class="pl4wavb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:save" /></template>
