<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4p45cnlu.css';
import '../../css/a/a12tcab1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="t4p45cnlu"/><path class="a12tcab1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:telescope" /></template>
