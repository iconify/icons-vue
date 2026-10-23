<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9x7_fvwo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9x7_fvwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:wrench-off" /></template>
