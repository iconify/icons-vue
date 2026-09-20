<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeuusybaq.css';
import '../../css/d/d38qlsbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeuusybaq"/><path class="d38qlsbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:translate" /></template>
