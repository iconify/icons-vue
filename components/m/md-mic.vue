<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9j9d9bcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j9j9d9bcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-mic" /></template>
