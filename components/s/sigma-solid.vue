<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu-umyrwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu-umyrwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sigma-solid" /></template>
