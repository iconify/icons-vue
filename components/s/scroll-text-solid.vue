<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb1qi_bbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb1qi_bbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scroll-text-solid" /></template>
