<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5ybebqpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5ybebqpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:terminal-solid" /></template>
