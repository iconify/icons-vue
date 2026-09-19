<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw_y8qb2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tw_y8qb2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:moonwave" /></template>
