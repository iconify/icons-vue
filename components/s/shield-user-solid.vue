<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/on85g6bhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="on85g6bhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:shield-user-solid" /></template>
