<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i95u-8bjy.css';
import '../../css/d/dxyzwm2nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="i95u-8bjy"/><path class="dxyzwm2nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:volume-unmuted-fill-16" /></template>
