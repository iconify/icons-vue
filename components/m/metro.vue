<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jr7-fdb9w.css';
import '../../css/r/rcg--6eak.css';
import '../../css/j/jzoz2c3ar.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jr7-fdb9w"/><path class="rcg--6eak"/><path class="jzoz2c3ar"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:metro" /></template>
