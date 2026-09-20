<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/y/ym5aw5b8u.css';
import '../../css/s/smdkeehst.css';
import '../../css/v/vbcgq2ytz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ym5aw5b8u"/><path class="smdkeehst"/><path class="vbcgq2ytz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:water-linear" /></template>
