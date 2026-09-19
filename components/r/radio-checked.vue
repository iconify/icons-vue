<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz-fc7bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mz-fc7bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:radio-checked" /></template>
