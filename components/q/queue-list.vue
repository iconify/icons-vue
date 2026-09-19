<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i188si0ua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i188si0ua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:queue-list" /></template>
