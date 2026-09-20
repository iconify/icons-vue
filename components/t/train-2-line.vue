<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa9vivbyh.css';
import '../../css/n/nzums1brs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oa9vivbyh"/><path class="nzums1brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:train-2-line" /></template>
