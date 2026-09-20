<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o17j_ibqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="o17j_ibqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:waves" /></template>
