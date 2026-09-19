<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cs6pq-bug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cs6pq-bug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:zoom-in" /></template>
