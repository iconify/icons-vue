<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bu1g5acvh.css';
import '../../css/k/kq1i8jlgx.css';
import '../../css/q/qbfao4-vr.css';
import '../../css/r/rbqpjolra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bu1g5acvh"/><path class="kq1i8jlgx"/><path class="qbfao4-vr"/><path class="rbqpjolra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:newspaper-outline" /></template>
