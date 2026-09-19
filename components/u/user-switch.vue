<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/q/qf-hi6bgl.css';
import '../../css/a/a8neukw-z.css';
import '../../css/m/m6iic4zxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qf-hi6bgl"/><circle class="a8neukw-z"/><path class="m6iic4zxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:user-switch" /></template>
