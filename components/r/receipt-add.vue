<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/jbe9hb-ly.css';
import '../../css/s/sudgglpna.css';
import '../../css/m/mbuyzmbrn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jbe9hb-ly"/><path class="sudgglpna"/><path class="mbuyzmbrn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:receipt-add" /></template>
