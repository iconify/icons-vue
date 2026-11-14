<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/p/p2705r1-z.css';
import '../../css/g/g48w89bvm.css';
import '../../css/y/yx1j7mbhh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2705r1-z"/><path class="g48w89bvm"/><path class="yx1j7mbhh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:money-receive-01" /></template>
