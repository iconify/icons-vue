<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bdneszcxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":480};
const content = `<path class="bdneszcxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:smartphone-erase" /></template>
