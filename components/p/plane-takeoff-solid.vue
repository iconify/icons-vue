<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8d4iybyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8d4iybyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plane-takeoff-solid" /></template>
