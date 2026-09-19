<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmks5cc2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vmks5cc2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:position" /></template>
