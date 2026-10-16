<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jno6ojglm.css';
import '../../css/y/yrc3asegu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jno6ojglm"/><path class="yrc3asegu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spillway-48-bold" /></template>
