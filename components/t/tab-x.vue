<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_k6wxb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_k6wxb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:tab-x" /></template>
