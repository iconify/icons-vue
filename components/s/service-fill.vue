<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfgs5d_bi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfgs5d_bi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:service-fill" /></template>
