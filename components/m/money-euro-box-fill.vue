<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvgi-id7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvgi-id7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:money-euro-box-fill" /></template>
