<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpfslacob.css';
import '../../css/d/dq9_gaclr.css';
import '../../css/c/clvzc9bjd.css';
import '../../css/v/vciy_oxlq.css';
import '../../css/n/nge6tfbxp.css';
import '../../css/p/pl74cqb7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="gpfslacob"/><circle class="dq9_gaclr"/><circle class="clvzc9bjd"/><circle class="vciy_oxlq"/><circle class="nge6tfbxp"/><path class="pl74cqb7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:qq-plot" /></template>
