<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lttz-hbsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="lttz-hbsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:panorama" /></template>
