<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi3532bvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":20};
const content = `<path class="oi3532bvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:orientaton" /></template>
