<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op4b25bpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op4b25bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:tally-four" /></template>
