<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt4w5s_mf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wt4w5s_mf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:overweight-person-standing" /></template>
