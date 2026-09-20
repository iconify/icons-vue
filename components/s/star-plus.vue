<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq-xevz_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq-xevz_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:star-plus" /></template>
