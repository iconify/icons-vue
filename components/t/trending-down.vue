<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb3-mo94e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bb3-mo94e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:trending-down" /></template>
