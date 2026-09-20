<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/ld5x_6a-q.css';
import '../../css/h/h8g36l7qt.css';
import '../../css/i/i8vpebqdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ld5x_6a-q"/><path class="h8g36l7qt"/><path class="i8vpebqdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:print" /></template>
