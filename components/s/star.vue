<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boe3m2q7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="boe3m2q7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:star" /></template>
