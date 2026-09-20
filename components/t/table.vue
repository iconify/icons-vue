<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrm_dri2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="zrm_dri2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:table" /></template>
