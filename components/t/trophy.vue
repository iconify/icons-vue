<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rg74h9u7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rg74h9u7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:trophy" /></template>
