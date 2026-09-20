<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qw_bnfbfv.css';
import '../../css/q/q5r6g9iuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":684.206};
const content = `<path class="qw_bnfbfv"/><path class="q5r6g9iuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:whole-foods-market" /></template>
