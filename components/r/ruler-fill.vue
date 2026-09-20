<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzkm-3f9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzkm-3f9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ruler-fill" /></template>
