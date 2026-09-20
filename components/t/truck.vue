<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esytgzliu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="esytgzliu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:truck" /></template>
