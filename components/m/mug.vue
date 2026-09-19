<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiozjq8dd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fiozjq8dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:mug" /></template>
