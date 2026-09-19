<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vppke0bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vppke0bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:underweight-24px" /></template>
