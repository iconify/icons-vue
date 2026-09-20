<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6jb2xjee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6jb2xjee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:tree-pine" /></template>
