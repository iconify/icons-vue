<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vb14ysbvz.css';
import '../../css/m/mhwhjcbvw.css';
import '../../css/a/a8coxybhr.css';
import '../../css/w/w7qfhsb1m.css';
import '../../css/r/rncbqcckd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><rect class="vb14ysbvz"/><path clip-rule="evenodd" class="mhwhjcbvw"/><path clip-rule="evenodd" class="a8coxybhr"/><path clip-rule="evenodd" class="w7qfhsb1m"/><path clip-rule="evenodd" class="rncbqcckd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:pg" /></template>
