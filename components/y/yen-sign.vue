<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g33lylbab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":320,"height":512};
const content = `<path class="g33lylbab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:yen-sign" /></template>
