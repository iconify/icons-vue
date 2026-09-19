<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_yfkbc0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q_yfkbc0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:pc" /></template>
