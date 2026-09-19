<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_mvxfbud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j_mvxfbud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:user-follow-fill-16" /></template>
