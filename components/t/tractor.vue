<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_q6bmblh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="v_q6bmblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:tractor" /></template>
