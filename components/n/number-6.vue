<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7n4f2bcl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7n4f2bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:number-6" /></template>
