<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa84dcblj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oa84dcblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:slightly-smiling-face" /></template>
