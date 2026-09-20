<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/k/kmj_7ubfc.css';
import '../../css/l/lx14d1bki.css';
import '../../css/u/u3r5afb8y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kmj_7ubfc"/><path class="lx14d1bki"/><path class="u3r5afb8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:messages2" /></template>
