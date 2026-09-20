<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxsavgw-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1416,"height":1591};
const content = `<path class="yxsavgw-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:prosus" /></template>
