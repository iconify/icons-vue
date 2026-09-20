<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ked47iboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ked47iboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:t-bar-lift" /></template>
