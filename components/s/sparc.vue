<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqse9p3cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":286,"height":512};
const content = `<path class="eqse9p3cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:sparc" /></template>
