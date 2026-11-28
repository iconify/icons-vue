<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcit-ab7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcit-ab7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:message-square-star" /></template>
