<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p_s3ipqpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p_s3ipqpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:undo" /></template>
