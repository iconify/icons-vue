<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td162ub0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":750,"height":850};
const content = `<path class="td162ub0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="il:users" /></template>
