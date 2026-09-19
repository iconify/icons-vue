<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e984jd2wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e984jd2wf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:shield-fill-exclamation" /></template>
