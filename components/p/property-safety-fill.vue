<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmi7ps-qu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mmi7ps-qu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:property-safety-fill" /></template>
