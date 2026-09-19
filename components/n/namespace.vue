<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd322u6xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kd322u6xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:namespace" /></template>
