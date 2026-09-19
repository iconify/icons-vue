<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wai40rbwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wai40rbwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:table-col-before" /></template>
