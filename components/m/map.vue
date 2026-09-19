<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d_r8p65rz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="d_r8p65rz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:map" /></template>
