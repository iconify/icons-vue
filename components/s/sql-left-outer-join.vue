<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ownzj_vcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ownzj_vcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sql-left-outer-join" /></template>
