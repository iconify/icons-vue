<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntlbgtbho.css';
import '../../css/f/f-ksdqydc.css';
import '../../css/j/j5z--zobz.css';
import '../../css/t/tffiggcyh.css';
import '../../css/g/guadj6bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="ntlbgtbho"/><circle class="f-ksdqydc"/><circle class="j5z--zobz"/><circle class="tffiggcyh"/><path class="guadj6bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:service-levels" /></template>
