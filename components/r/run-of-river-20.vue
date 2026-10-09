<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwfb0b_qf.css';
import '../../css/q/qxaxj2trm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qwfb0b_qf"/><path class="qxaxj2trm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:run-of-river-20" /></template>
