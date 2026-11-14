<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/j3-denbmb.css';
import '../../css/i/ink891bfz.css';
import '../../css/y/y5c-b7h0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j3-denbmb"/><path class="ink891bfz"/><path class="y5c-b7h0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-add-01" /></template>
