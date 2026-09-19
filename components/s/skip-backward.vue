<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjyw_p0_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gjyw_p0_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:skip-backward" /></template>
