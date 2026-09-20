<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_6nx6bhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m_6nx6bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:open-envelope-right-with-shekel" /></template>
