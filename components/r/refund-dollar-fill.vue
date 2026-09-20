<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gu1amlj5r.css';
import '../../css/m/mn6i_fowy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu1amlj5r"/><path class="mn6i_fowy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:refund-dollar-fill" /></template>
