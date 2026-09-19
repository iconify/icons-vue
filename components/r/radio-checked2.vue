<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op_rvexja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="op_rvexja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:radio-checked2" /></template>
