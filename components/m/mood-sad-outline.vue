<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s1dozmb8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s1dozmb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:mood-sad-outline" /></template>
