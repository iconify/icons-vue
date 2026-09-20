<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8-uw-btt.css';
import '../../css/t/tmcxzhbqx.css';
import '../../css/c/c3ivfk8mr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="g8-uw-btt"/><path class="tmcxzhbqx"/><path class="c3ivfk8mr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:other-ui-target" /></template>
