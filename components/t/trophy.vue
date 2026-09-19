<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekgwi8jyj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ekgwi8jyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:trophy" /></template>
