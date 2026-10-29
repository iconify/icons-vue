<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3kx2obxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3kx2obxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-right-solid" /></template>
