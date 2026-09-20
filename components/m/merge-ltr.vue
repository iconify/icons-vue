<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxsq5cb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bxsq5cb_w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:merge-ltr" /></template>
