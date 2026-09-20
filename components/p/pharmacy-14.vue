<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gys2f-bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="gys2f-bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:pharmacy-14" /></template>
