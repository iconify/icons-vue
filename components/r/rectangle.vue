<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3t9q1bdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3t9q1bdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rectangle" /></template>
