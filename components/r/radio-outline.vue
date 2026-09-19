<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdsn85ysj.css';
import '../../css/x/xk4xuvuka.css';
import '../../css/x/xfngl4bbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdsn85ysj"/><path class="xk4xuvuka"/><path class="xfngl4bbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:radio-outline" /></template>
