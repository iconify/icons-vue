<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wq0ony_kv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wq0ony_kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:task-progress" /></template>
