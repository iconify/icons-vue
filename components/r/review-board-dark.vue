<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3rjk_xzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q3rjk_xzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:review-board-dark" /></template>
