<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hy_v726cn.css';
import '../../css/v/vz494t6ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hy_v726cn"/><path class="vz494t6ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:stop-sign-1" /></template>
