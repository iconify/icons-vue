<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvstrjjvh.css';
import '../../css/e/e_k2sgbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="nvstrjjvh"/><path class="e_k2sgbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:nezha-light" /></template>
