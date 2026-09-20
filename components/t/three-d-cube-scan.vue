<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/e/erzeiv-ot.css';
import '../../css/w/whgfoj3ew.css';
import '../../css/z/z6bfi4byi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="erzeiv-ot"/><path class="whgfoj3ew"/><path class="z6bfi4byi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:three-d-cube-scan" /></template>
