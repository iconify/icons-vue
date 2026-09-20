<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8k4hcbvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8k4hcbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:snapchat" /></template>
