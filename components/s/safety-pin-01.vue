<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/r3v884hcy.css';
import '../../css/g/g1ere0j-x.css';
import '../../css/y/y7ql6fbwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3v884hcy"/><circle class="g1ere0j-x"/><path class="y7ql6fbwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:safety-pin-01" /></template>
