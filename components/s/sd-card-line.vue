<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck-suz5qq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck-suz5qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:sd-card-line" /></template>
