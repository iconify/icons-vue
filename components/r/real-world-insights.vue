<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/t/t_ev7s-sv.css';
import '../../css/p/py_4k92_q.css';
import '../../css/q/qa3awcbml.css';
import '../../css/g/g32u12b2q.css';
import '../../css/m/m6a-39ccf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g transform="translate(-2.4 -2)" class="bi12bsetm"><path class="t_ev7s-sv"/><circle class="py_4k92_q"/><circle class="qa3awcbml"/><circle class="g32u12b2q"/><path class="m6a-39ccf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:real-world-insights" /></template>
