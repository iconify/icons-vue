<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrl42bkxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrl42bkxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:play" /></template>
