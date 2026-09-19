<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-foc9irl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a-foc9irl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:suitcase-line" /></template>
