<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j9p79zvwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j9p79zvwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:speedometer" /></template>
