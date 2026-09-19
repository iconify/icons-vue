<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp6hhk2lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kp6hhk2lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:upc-scan" /></template>
