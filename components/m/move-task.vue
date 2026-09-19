<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y22y27b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y22y27b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:move-task" /></template>
