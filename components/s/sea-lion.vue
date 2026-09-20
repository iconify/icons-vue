<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qv8q9zall.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qv8q9zall"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:sea-lion" /></template>
