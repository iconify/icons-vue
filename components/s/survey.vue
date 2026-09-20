<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs37-c-kd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="qs37-c-kd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:survey" /></template>
