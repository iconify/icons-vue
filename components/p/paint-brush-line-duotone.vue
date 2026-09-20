<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/r/rgpbbbb1c.css';
import '../../css/j/j2fajacou.css';
import '../../css/t/tg3ffvmkc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rgpbbbb1c"/><path class="j2fajacou"/><path class="tg3ffvmkc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:paint-brush-line-duotone" /></template>
