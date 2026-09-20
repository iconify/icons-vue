<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojc1q_ioi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ojc1q_ioi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:shell-window-maximize-outline" /></template>
