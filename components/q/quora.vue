<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrre60oiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="vrre60oiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:quora" /></template>
