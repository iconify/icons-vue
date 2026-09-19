<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/v/v-zj4qbyf.css';
import '../../css/g/gx4bnzbrp.css';
import '../../css/j/j1fvgp9vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v-zj4qbyf"/><path class="gx4bnzbrp"/><path class="j1fvgp9vr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:software-license" /></template>
