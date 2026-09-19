<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ogt714bjg.css';
import '../../css/t/trltflb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ogt714bjg"/><path class="trltflb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-tools" /></template>
