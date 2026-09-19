<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9_07c7vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="i9_07c7vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:merge" /></template>
