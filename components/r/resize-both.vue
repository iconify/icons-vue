<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vn5otgbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="vn5otgbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:resize-both" /></template>
