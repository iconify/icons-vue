<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iocgcpb9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="iocgcpb9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:warning" /></template>
