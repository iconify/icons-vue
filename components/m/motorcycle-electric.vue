<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lzm7kvups.css';
import '../../css/a/a-z24ibwd.css';
import '../../css/z/zp01jbboj.css';
import '../../css/p/pfgsr9b3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="lzm7kvups"/><circle class="a-z24ibwd"/><path class="zp01jbboj"/><path class="pfgsr9b3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="evicons:motorcycle-electric" /></template>
