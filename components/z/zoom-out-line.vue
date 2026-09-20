<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx-_zh9uq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx-_zh9uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:zoom-out-line" /></template>
