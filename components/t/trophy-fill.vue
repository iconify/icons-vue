<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq1hqm0hv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq1hqm0hv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:trophy-fill" /></template>
