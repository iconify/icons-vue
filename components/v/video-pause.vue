<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql-63ojvj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ql-63ojvj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:video-pause" /></template>
