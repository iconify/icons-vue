<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvhnz1kyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lvhnz1kyg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shield" /></template>
