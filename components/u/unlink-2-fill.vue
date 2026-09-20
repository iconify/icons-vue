<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylog8lipq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylog8lipq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unlink-2-fill" /></template>
