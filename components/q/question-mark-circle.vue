<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyhf-2_bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyhf-2_bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:question-mark-circle" /></template>
