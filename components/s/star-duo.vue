<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ga618bbrt.css';
import '../../css/s/s1qbo6fdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ga618bbrt secondary"/><path class="primary s1qbo6fdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:star-duo" /></template>
