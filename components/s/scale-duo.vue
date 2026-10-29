<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/o/op2_qvb8o.css';
import '../../css/k/k84vtocml.css';
import '../../css/b/bropegbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="op2_qvb8o wm-a"/><path class="k84vtocml"/><path class="bropegbcq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scale-duo" /></template>
