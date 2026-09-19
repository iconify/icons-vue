<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n001-1bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n001-1bpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:rotate-ccw" /></template>
