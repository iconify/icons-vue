<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjjuqebdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjjuqebdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:rhombus" /></template>
