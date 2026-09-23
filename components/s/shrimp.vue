<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epqtf34dc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epqtf34dc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:shrimp" /></template>
