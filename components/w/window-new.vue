<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvr2w2bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lvr2w2bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:window-new" /></template>
