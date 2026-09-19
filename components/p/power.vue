<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5ce7xbrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a5ce7xbrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:power" /></template>
