<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqt1wjcwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqt1wjcwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:text-bar" /></template>
