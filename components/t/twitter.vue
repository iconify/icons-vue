<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hikc1cclf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hikc1cclf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:twitter" /></template>
