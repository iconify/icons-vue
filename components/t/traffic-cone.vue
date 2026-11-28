<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el-65cbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el-65cbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:traffic-cone" /></template>
