<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zv_y85bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zv_y85bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icomoon-free:wondering2" /></template>
