<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bifw8lj3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bifw8lj3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:newline-ltr" /></template>
