<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uykqjq0kh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uykqjq0kh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:sidebar-x" /></template>
