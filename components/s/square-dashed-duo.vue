<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-78pm1dc.css';
import '../../css/s/s146rvdmi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-78pm1dc secondary"/><path class="primary s146rvdmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:square-dashed-duo" /></template>
