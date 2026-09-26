<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/rb-l41-ka.css';
import '../../css/j/jrvuve-_c.css';
import '../../css/x/x1f4lc3zb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rb-l41-ka"/><path class="jrvuve-_c"/><path class="x1f4lc3zb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:separator-vertical-linear" /></template>
