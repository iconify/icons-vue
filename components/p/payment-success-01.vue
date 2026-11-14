<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/j3-denbmb.css';
import '../../css/x/x141tmu0b.css';
import '../../css/t/tvgnlnb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j3-denbmb"/><path class="x141tmu0b"/><path class="tvgnlnb2f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:payment-success-01" /></template>
