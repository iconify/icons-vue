<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/atfst2bbd.css';
import '../../css/x/xk80sybyi.css';
import '../../css/t/tc2fj349v.css';
import '../../css/v/velq4uheh.css';
import '../../css/g/gdgn-sbca.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="atfst2bbd"/><path class="xk80sybyi"/><path class="tc2fj349v"/><path class="velq4uheh"/><path class="gdgn-sbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pie-chart-twotone" /></template>
