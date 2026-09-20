<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hd-jtvbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hd-jtvbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trpc" /></template>
