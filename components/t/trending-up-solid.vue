<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/itwz0zbrd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itwz0zbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:trending-up-solid" /></template>
