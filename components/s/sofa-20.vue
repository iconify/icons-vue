<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycu-hhf9w.css';
import '../../css/g/g3yqyfbnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ycu-hhf9w"/><path class="g3yqyfbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sofa-20" /></template>
