<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb3s7_7hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="bb3s7_7hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:user-o" /></template>
