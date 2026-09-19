<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yy_d4cc_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="yy_d4cc_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mosquito-net" /></template>
