<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqzvm0boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yqzvm0boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:smartphone" /></template>
