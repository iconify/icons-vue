<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe_m16lxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fe_m16lxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:scroll-text" /></template>
