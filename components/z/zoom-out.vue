<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4b8d0nzv.css';
import '../../css/k/kzui9exaw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p4b8d0nzv"/><path class="kzui9exaw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:zoom-out" /></template>
