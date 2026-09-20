<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d99w1wg2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="d99w1wg2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:stamp" /></template>
