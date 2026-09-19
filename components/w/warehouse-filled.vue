<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl2o4cc0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl2o4cc0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:warehouse-filled" /></template>
