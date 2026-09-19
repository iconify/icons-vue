<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c76bwnbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c76bwnbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:signal-1" /></template>
