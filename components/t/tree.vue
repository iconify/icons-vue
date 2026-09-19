<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0_m2zb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a0_m2zb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:tree" /></template>
