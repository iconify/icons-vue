<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp1vynl4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="yp1vynl4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-cane" /></template>
