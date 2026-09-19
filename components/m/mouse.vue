<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlx2_7l6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wlx2_7l6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:mouse" /></template>
