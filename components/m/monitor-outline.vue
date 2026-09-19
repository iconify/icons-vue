<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-1zzmbde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="v-1zzmbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:monitor-outline" /></template>
