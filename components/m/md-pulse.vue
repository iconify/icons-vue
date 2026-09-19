<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_e_t9pnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="q_e_t9pnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-pulse" /></template>
