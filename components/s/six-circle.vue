<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/fchbuq2ke.css';
import '../../css/f/fvgh-ccoe.css';
import '../../css/g/g4zs08s-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fchbuq2ke"/><path class="fvgh-ccoe"/><path class="g4zs08s-q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:six-circle" /></template>
