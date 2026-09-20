<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxk8nxb5e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxk8nxb5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:yuque-line" /></template>
