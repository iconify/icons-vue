<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npq4jthxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npq4jthxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:tag-minus-outline" /></template>
