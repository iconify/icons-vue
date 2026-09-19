<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shvltlb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="shvltlb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:phone-vibrate-fill" /></template>
