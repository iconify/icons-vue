<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lyq_zyido.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyq_zyido"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:subtract-line" /></template>
